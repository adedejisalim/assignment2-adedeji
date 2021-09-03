# Salim Adedeji
## Favorite place: Dubai
My favorite place is Dubai because of the **scenery** and just the **different activities** it has to offer. 

---

# Directions to Dubai
1. Drive to kansas city
2. Get into airport 
    1. Check in Luggage
    2. Board the Flight
3. Land at Dubai Airport
    1. Collect checked bags
    2. Leave the airport
4. Visit places in Dubai

Things to Bring:
* Clothes
* Money
* Sneakers
* Jewelry

[Click Here to know About Me](AboutME.md)

---

# Food Table
This section will introduce you to different foods I would recommend you to try.

| Food/Drink | Where to find | Amount |
| ---        | ---           | ---    |
| Jollof Rice| Nigeria       | $15    |
| Peri Peri  | London        | $20    |
| Ramen      | Japan         | $5     |
| Schewepps  | Nigeria       | $2     |


---

# Pithy Quotes

> The greatest glory in living lies not in never falling, but in rising every time we fall. *- Nelson Mandela*

> If you look at what you have in life, you'll always have more. If you look at what you don't have in life, you'll never have enough. *- Oprah Winfrey* 

---

# Code Fencing

> Breadth First Search (BFS) algorithm traverses a graph in a breadthward motion and uses a queue to remember to get the next vertex to start a search, when a dead end occurs in any iteration.

[Click here to find out more about BFS](https://www.tutorialspoint.com/data_structures_algorithms/breadth_first_traversal.htm)

```
mmn vector<vector<int>> adj;  // adjacency list representation
int n; // number of nodes
int s; // source vertex

queue<int> q;
vector<bool> used(n);
vector<int> d(n), p(n);

q.push(s);
used[s] = true;
p[s] = -1;
while (!q.empty()) {
    int v = q.front();
    q.pop();
    for (int u : adj[v]) {
        if (!used[u]) {
            used[u] = true;
            q.push(u);
            d[u] = d[v] + 1;
            p[u] = v;
        }
    }
}
```

<https://cp-algorithms.com/index.html>

