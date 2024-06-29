# NeetCode 150 Notes

## Arrays & Hashing

- [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/): convert to set
- [Valid Anagram](https://leetcode.com/problems/valid-anagram/): compare counts
- [Two Sum](https://leetcode.com/problems/two-sum/): hashmap containing seen numbers
- [Group Anagrams](https://leetcode.com/problems/group-anagrams/): use count as key in hashmap
- [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/): count then bucket sort by frequency 
- [Encode and Decode Strings](https://neetcode.io/problems/string-encode-and-decode): string length and delimiter before each string
- [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/): store prefix and suffix directly in result array
- [Valid Sudoku](https://leetcode.com/problems/valid-sudoku/): use a helper function
- [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/): use set and check the start of each sequence 

## Two Pointers

- [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/): compare left and right pointer
- [Two Sum II - Input Array is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/): increment left if sum is too small, decrement right if sum is too big
- [3Sum](https://leetcode.com/problems/3sum/): sort then do two sum for each
- [Container with Most Water](https://leetcode.com/problems/container-with-most-water/): increment left if smaller, decrement right if smaller
- [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/): 

## Stack

- [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/): use a stack
- [Min Stack](https://leetcode.com/problems/min-stack/): save tuples containing the value and min at insertion time in the stack
- [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/): use a stack and evaluate directly
- [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/): backtrack by adding openers and closers if can be added
- [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/): keep monotonic decreasing stack
- [Car Fleet](https://leetcode.com/problems/car-fleet/): create monotonic stack by decreasing position
- [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/):

## Binary Search

- [Binary Search](https://leetcode.com/problems/binary-search/): binary search
- [Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/): convert to 1-D
- [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/): binary search for k
- [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/):
- [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/):
- [Time Based Key Value Store](https://leetcode.com/problems/time-based-key-value-store/):
- [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/):

## Sliding Window

- [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/): keep left at the minimum so far and track max difference
- [Longest Substring without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/): track window's character counts
- [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/):
- [Permutation in String](https://leetcode.com/problems/permutation-in-string/):
- [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/):
- [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/):

## Linked List

- [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/): recursively modify pointers
- [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/): recursively set smaller's pointer to larger
- [Reorder List](https://leetcode.com/problems/reorder-list/): find middle, reverse second half, then merge
- [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/): use second pointer n nodes ahead
- [Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/): one pass to create the list, one pass to set pointers. use hashmap
- [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/): track carry
- [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/): slow/fast pointer
- [Find The Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/): slow/fast pointer
- [LRU Cache](https://leetcode.com/problems/lru-cache/): use a hashmap and doubly linkedlist from least recently to most recently used
- [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/): use heap to track next node each time
- [Reverse Nodes in K Group](https://leetcode.com/problems/reverse-nodes-in-k-group/): use helper function to reverse then do each group

## Trees

- [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/): recursively switch left and right child
- [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/): recursively find max depth of each child
- [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/):
- [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/): create a recursive height function that checks the two children's height then returns its own
- [Same Tree](https://leetcode.com/problems/same-tree/): recursively check each child
- [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/): serialize to strings
- [Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/): recursively check each case based on the values then go into the correct subtree
- [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/): dfs by level
- [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/): modified level order traversal
- [Count Good Nodes in Binary Tree](https://leetcode.com/problems/count-good-nodes-in-binary-tree/): recursively check if value is less than max and call on children with new max
- [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/): track desired min and max values then recursively check children
- [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/): stack traverse
- [Contruct Binary Tree From Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/):
- [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/):
- [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/):

## Tries

- [Implement Trie Prefix Tree](https://leetcode.com/problems/implement-trie-prefix-tree/): nested hashmaps
- [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/): use a trie with marked word ends
- [Word Search II](https://leetcode.com/problems/word-search-ii/): use a trie then backtrack starting at each position, marking obtained words by removing their end marker

## Backtracking

- [Subsets](https://leetcode.com/problems/subsets/): iterative
- [Combination Sum](https://leetcode.com/problems/combination-sum/):
- [Permumations](https://leetcode.com/problems/permutations/):
- [Subsets II](https://leetcode.com/problems/subsets-ii/):
- [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/):
- [Word Search](https://leetcode.com/problems/word-search/):
- [Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/):
- [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/):
- [N Queens](https://leetcode.com/problems/n-queens/):

## Heap

- [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/):
- [Last Stone Weight](https://leetcode.com/problems/last-stone-weight/):
- [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/):
- [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/):
- [Task Scheduler](https://leetcode.com/problems/task-scheduler/):
- [Design Twitter](https://leetcode.com/problems/design-twitter/):
- [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/):

## Graphs

- [Number of Islands](https://leetcode.com/problems/number-of-islands/):
- [Max Area of Island](https://leetcode.com/problems/max-area-of-island/):
- [Clone Graph](https://leetcode.com/problems/clone-graph/):
- [Walls and Gates](https://leetcode.com/problems/walls-and-gates/):
- [Rotting Oranges](https://leetcode.com/problems/rotting-oranges/):
- [Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/):
- [Surrounded Regions](https://leetcode.com/problems/surrounded-regions/):
- [Course Schedule](https://leetcode.com/problems/course-schedule/):
- [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/):
- [Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/):
- [Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/):
- [Redundant Connection](https://leetcode.com/problems/redundant-connection/):
- [Word Ladder](https://leetcode.com/problems/word-ladder/):

## Advanced Graphs

- [Reconstruct Itinerary](https://leetcode.com/problems/reconstruct-itinerary/):
- [Min Cost to Connect All Points](https://leetcode.com/problems/min-cost-to-connect-all-points/):
- [Network Delay Time](https://leetcode.com/problems/network-delay-time/):
- [Swim in Rising Water](https://leetcode.com/problems/swim-in-rising-water/):
- [Alien Dictionary](https://leetcode.com/problems/alien-dictionary/):
- [Cheapest Flights within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/):

## 1-D DP

- [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/):
- [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/):
- [House Robber](https://leetcode.com/problems/house-robber/):
- [House Robber II](https://leetcode.com/problems/house-robber-ii/):
- [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/):
- [Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/):
- [Decode Ways](https://leetcode.com/problems/decode-ways/):
- [Coin Change](https://leetcode.com/problems/coin-change/):
- [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/):
- [Word Break](https://leetcode.com/problems/word-break/):
- [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/):
- [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/):

## 2-D DP

- [Unique Paths](https://leetcode.com/problems/unique-paths/):
- [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/):
- [Best Time to Buy and Sell Stock with Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/):
- [Coin Change II](https://leetcode.com/problems/coin-change-ii/):
- [Target Sum](https://leetcode.com/problems/target-sum/):
- [Interleaving String](https://leetcode.com/problems/interleaving-string/):
- [Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/):
- [Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/):
- [Edit Distance](https://leetcode.com/problems/edit-distance/):
- [Burst Balloons](https://leetcode.com/problems/burst-balloons/):
- [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/):

## Intervals

- [Insert Interval](https://leetcode.com/problems/insert-interval/):
- [Merge Interval](https://leetcode.com/problems/merge-intervals/):
- [Non Overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/):
- [Meeting Rooms](https://leetcode.com/problems/meeting-rooms/):
- [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/):
- [Minimum Interval to Include Each Query](https://leetcode.com/problems/minimum-interval-to-include-each-query/):

## Greedy

- [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/):
- [Jump Game](https://leetcode.com/problems/jump-game/):
- [Jump Game II](https://leetcode.com/problems/jump-game-ii/):
- [Gas Station](https://leetcode.com/problems/gas-station/):
- [Hand of Straights](https://leetcode.com/problems/hand-of-straights/):
- [Merge Triplets to Form Target Triplet](https://leetcode.com/problems/merge-triplets-to-form-target-triplet/):
- [Partition Labels](https://leetcode.com/problems/partition-labels/):
- [Valid Parenthesis String](https://leetcode.com/problems/valid-parenthesis-string/):

## Bit Manipulation

- [Single Number](https://leetcode.com/problems/single-number/):
- [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/):
- [Counting Bits](https://leetcode.com/problems/counting-bits/):
- [Reverse Bits](https://leetcode.com/problems/reverse-bits/):
- [Missing Number](https://leetcode.com/problems/missing-number/):
- [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/):
- [Reverse Integer](https://leetcode.com/problems/reverse-integer/):

## Math

- [Rotate Image](https://leetcode.com/problems/rotate-image/):
- [Spiral Matrix](https://leetcode.com/problems/spiral-matrix/):
- [Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/):
- [Happy Number](https://leetcode.com/problems/happy-number/):
- [Plus One](https://leetcode.com/problems/plus-one/):
- [Pow(x, n)](https://leetcode.com/problems/powx-n/):
- [Multiply Strings](https://leetcode.com/problems/multiply-strings/):
- [Detect Squares](https://leetcode.com/problems/detect-squares/):
