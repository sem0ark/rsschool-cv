# Arkadii Semenov

Contacts:

- +381637009535
- arcadii.sem@gmail.com
- https://github.com/sem0ark
- https://www.linkedin.com/in/semenovam/

## Currently

Student on "Software Engineering" program in Metropolitan University, Belgrade, Serbia.

## About me

I am a curious student striving for knowledge and acquiring new skills to achieve self-expression with code and diagrams.

Characteristics:

- Quick learner, Self-learner, Curious
- Persistent, Polite, Organized

## Education

`2022-2026` Current
**Metropolitan University, Belgrade, Serbia**

- "Software Engineering", year 2

`2020-2022`
**Industrial and Commercial lyceum, Vladimir, Russia**

- GPA 5.0/5.0
- Profile: "Mathematics and computer science"
- Specialization: "Computer Operator"
- ![Competition Certificates](https://drive.google.com/file/d/1mRQKKAF4KSiHceQjghMjt5U-pU9IMgOU/view?usp=sharing)

### Course programs

- "Google Cloud Get Certified program" Associate Cloud Engineer
- "EPAM UpSkillMe - Node.js development" Mentoring program
- "Yandex Summer School - User Interface Development School", completed stage 1

## Skills

### Code examples

LeetCode problem:

```python
# Profile: https://leetcode.com/pocket_30/
class Graph:
    def __init__(self, n: int, edges: List[List[int]]):
        self.g = defaultdict(list)
        self.n = n
        for a, b, c in edges: self.g[a].append((c, b))


    def addEdge(self, edge: List[int]) -> None:
        self.g[edge[0]].append((edge[2], edge[1]))


    def shortestPath(self, node1: int, node2: int) -> int:
        q = [(0, node1)]
        dist = [inf] * self.n

        while q:
            cost, cur = heappop(q)
            if cur == node2: return cost
            for c, nxt in self.g[cur]:
                if dist[nxt] > cost + c:
                    dist[nxt] = cost + c
                    heappush(q, (cost + c, nxt))
        return -1
```

CodeWars problem solution:

```js
// Profile: https://www.codewars.com/users/pocket%20bone
function domainName(url) {
  return url.match(
    /^(?:https?:\/\/)?(?:www\.)?([\w\-\d]+)(\.([][^:\/\n\?\=]+))?/im
  )[1];
}
```

### Links to
