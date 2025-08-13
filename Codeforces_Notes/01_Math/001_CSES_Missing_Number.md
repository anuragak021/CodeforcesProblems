# CSES Missing Number

### ### Problem [Link](https://cses.fi/problemset/task/1083/)

### ### Video [Link](https://www.youtube.com/watch?v=Hk4CihIt9-0&embeds_referring_euri=https%3A%2F%2Flegacy.asksenior.in%2F)

## 💡 Approaches

### 📌 Best Approach 
[The Lofic is to take the input and the match it with i + 1 in a sorted manner]
#### Code (C++)
```cpp
// [PASTE_YOUR_BEST_APPROACH_CODE_SOLUTION_HERE]
//हर हर महादेव
#include <bits/stdc++.h>
using namespace std;
#define int long long
#define anuragak021 ios::sync_with_stdio(false); cin.tie(NULL);

/*
    कर्मण्ये वाधिका रस्ते मा फलेषु कदाचन।
    मा कर्म फल हेतु र्भूर्मा ते सङ्गोऽस्त्व कर्मणि॥

    NO NEED TO CODE WITHOUT A COMPLETE ALGORITHM
    THINK OF WHAT THE PROBLEM DEMANDS!!!
*/

void solve(){
    int n;
    cin >> n;
    vector<int> vec;
    for(int i =0 ; i < n-1; ++i){
        int x;
        cin >> x;
        vec.push_back(x);
    }

    sort(vec.begin() , vec.end());
    for(int i = 0 ; i < n ; ++i){
        if(vec[i] != i + 1){
            cout << i + 1 << "\n";
            break;
        }
    }
}

int32_t main(){
    /*********************/ anuragak021 /*********************/
    srand(time(NULL));

    // freopen("input.txt", "r", stdin);
    // freopen("output.txt", "w", stdout);

    int t = 1;
    // cin >> t;
    while(t--){
        solve();
    }
    // cerr << "Time : " << 1000 * ((double)clock()) / (double)CLOCKS_PER_SEC << "ms";
    return 0;
}

```
#### TC and SC
- **Time Complexity:** [ADD_TIME_COMPLEXITY_HERE]
- **Space Complexity:** [ADD_SPACE_COMPLEXITY_HERE]

---

### Approach 1
[The logic is to take the input and then match it with i + 1 in a sorted manner]
#### Code (C++)
```cpp
// [PASTE_CODE_FOR_APPROACH_1_HERE]
//हर हर महादेव
#include <bits/stdc++.h>
using namespace std;
#define int long long
#define anuragak021 ios::sync_with_stdio(false); cin.tie(NULL);

/*
    कर्मण्ये वाधिका रस्ते मा फलेषु कदाचन।
    मा कर्म फल हेतु र्भूर्मा ते सङ्गोऽस्त्व कर्मणि॥

    NO NEED TO CODE WITHOUT A COMPLETE ALGORITHM
    THINK OF WHAT THE PROBLEM DEMANDS!!!
*/

void solve(){
    int n;
    cin >> n;
    vector<int> vec;
    for(int i =0 ; i < n-1; ++i){
        int x;
        cin >> x;
        vec.push_back(x);
    }

    sort(vec.begin() , vec.end());
    for(int i = 0 ; i < n ; ++i){
        if(vec[i] != i + 1){
            cout << i + 1 << "\n";
            break;
        }
    }
}

int32_t main(){
    /*********************/ anuragak021 /*********************/
    srand(time(NULL));

    // freopen("input.txt", "r", stdin);
    // freopen("output.txt", "w", stdout);

    int t = 1;
    // cin >> t;
    while(t--){
        solve();
    }
    // cerr << "Time : " << 1000 * ((double)clock()) / (double)CLOCKS_PER_SEC << "ms";
    return 0;
}

```
#### TC and SC
- **Time Complexity:** [O(N)]
- **Space Complexity:** [O(N)]

---

### Approach 2
[EXPLAIN_APPROACH_2_LOGIC_HERE]
#### Code (C++)
```cpp
// [PASTE_CODE_FOR_APPROACH_2_HERE]

```
#### TC and SC
- **Time Complexity:** [ADD_TIME_COMPLEXITY_HERE]
- **Space Complexity:** [ADD_SPACE_COMPLEXITY_HERE]

---

## 📝 Notes

[ADD_ANY_ADDITIONAL_NOTES_OR_KEY_TAKEAWAYS_HERE]
