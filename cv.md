# Arkadii Semenov

Contacts:

- +381637009535
- arcadii.sem@gmail.com
- https://github.com/sem0ark
- https://www.linkedin.com/in/semenovam/
- RS-School Discord server nickname: `Arkadii Semenov (@sem0ark)`

## Currently

Student on "Software Engineering" undergraduate program, will be completed in 2026.

## About me

I am a curious student striving for knowledge and acquiring new skills to become professional full-stack developer.

Characteristics:

- Quick learner, Self-learner, Curious
- Persistent, Polite, Organized

## Education

`2022-2026`
**Metropolitan University, Belgrade, Serbia**

- "Software Engineering"

`2020-2022`
**Industrial and Commercial lyceum, Vladimir, Russia**

- GPA 5.0/5.0
- Profile: "Mathematics and computer science"
- Specialization: "Computer Operator"

### Course programs and competitions

- ["Google Cloud Get Certified program" Associate Cloud Engineer](https://google.accredible.com/55dadb3f-afd0-4fed-8daf-753f8544efc4)
- ["EPAM UpSkillMe - Node.js development" Mentoring program](https://drive.google.com/file/d/13d513xmW8btwwoq5gpBk8yIT2Ur0gzo5/view?usp=sharing)
- "Yandex Summer School - User Interface Development School", completed stage 1
- [List of Competition Certificates](https://drive.google.com/file/d/1mRQKKAF4KSiHceQjghMjt5U-pU9IMgOU/view?usp=sharing)

### Projects

- [Website mockup with HTML&CSS](https://github.com/sem0ark/web_training/tree/master/front-end/220000%20resp_website)
- [Node API proxy with OpenWeather API](https://github.com/sem0ark/web_training/tree/master/node/node_api_proxy_server)
- [Ray tracer in C](https://github.com/sem0ark/c_cpp_training/tree/main/c_lang/simp_curses_ray_tracer)

## Skills

Programming:

- JavaScript (TypeScript, ES6, Node.js + Express)
- HTML5 & CSS3
- Python
- Java

Tools:

- Google Cloud Platform
- Git, GitHub and GitHub Actions, GitLab
- Jira, Confluence

Theoretical knowledge:

- Algorithms and Data Structures (Competitive programming)
- Coding and development practices (SOLID, OOP patterns)
- Software Engineering
  - Development processes (such as Agile + SCRUM)
- Programming paradigms:
  - Object-Oriented Programming (Java, Python, TS)
  - Functional programming (TS)
  - Procedure programming (C)
  - Logic programming (prolog)

Languages:

- Russian (Native)
- English (B2+/C1) [EF SET](https://www.efset.org/cert/n291tc)
- Serbian (B1)
- Slovak (B1)
- German (A1)

### Code examples

LeetCode problem:

```python
# Profile: https://leetcode.com/pocket_30/
class Graph:
    def __init__(self, n: int, edges: List[List[int]]):
        self.g = defaultdict(list)
        self.n = n
        for a, b, c in edges:
            self.g[a].append((c, b))


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
