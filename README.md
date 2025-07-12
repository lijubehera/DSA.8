#𝗗𝗮𝘆 𝟴 𝗼𝗳 𝗣𝘆𝘁𝗵𝗼𝗻 & 𝗗𝗦𝗔 𝗝𝗼𝘂𝗿𝗻𝗲𝘆
 💻 LeetCode Problem: Remove Duplicates from Sorted Array
 🔗 LeetCode Profile : https://lnkd.in/dVh3rC9d

🧩 Problem Statement:
 Given a sorted array, remove the duplicates in-place such that each unique element appears only once and return the new length.

Example:
 Input: [1,1,2]
 Output: [1,2] and return length 2
🔍 Logic Behind My Solution:
 ✔ Since the array is sorted, duplicates are adjacent.

 ✔ Use two pointers:
start keeps track of the last unique element
i loops over the array
 ✔ If current element is different from the last unique one → move it forward.
🧠 Key Line:
if nums[i] != nums[start]:
 start += 1
 nums[start] = nums[i]

📌 Final result: Only the first start+1 elements are unique.

🎯 Learnings Today:
 🔹 Applying the two-pointer technique for in-place array operations
 🔹 Gained intuition on how sorted arrays simplify logic
 🔹 Strengthened understanding of space optimization
