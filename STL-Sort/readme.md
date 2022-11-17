# Method 1: Standard (Accepted) 
Time: O(n * lgn)

```
void stlSort(vector<int>& nums) {
	sort(nums.begin(), nums.end());
}
```
# Method 2: Stable (Accepted) 
Time: O(n * lgn)

```
void stableStlSort(vector<int>& nums) {
	stable_sort(nums.begin(), nums.end());
}
```
