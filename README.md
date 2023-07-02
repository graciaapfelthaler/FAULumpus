# FAULumpus
Variant of the wumpus world localized to Erlangen and the FAU.

### Objective
Implement an agent that explores the FAULumpus world – a variant of the Wumpus World localized to Erlangen and the FAU. The FAULumpus world is on a 12 × 8 grid. You can explore any square that is adjacent to a square you have already explored. For example, if you have explored squares (0, 0), (0, 1), (1, 0), you could next explore the square (0, 2). On some of the squares you can find sights. Your goal is to find as many sights as possible without dying. If you find 𝑛 sights and then stop the exploration, you get 𝑛2 points. But if your agent dies, you get 0 points. Your agent dies if it steps onto a square with the Wumpus or if it steps onto a square that has a pit. As a warning sign, there is a smell or a breeze on the neighbouring squares.

<img width="298" alt="Bildschirm­foto 2023-07-02 um 14 09 13" src="https://github.com/graciaapfelthaler/FAULumpus/assets/118312966/2277ed35-518e-41e3-9342-d8c6123cd8ca">
