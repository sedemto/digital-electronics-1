# Lab 5: Peter Balušík
## 1. Equations
![eqn](img1.jpg)
## 2. Truth tables
 **D-type FF**
   | **clk** | **d** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](arrow.png) | 0 | 0 | 0 | `q(n+1)` has the same level as `d` |
   | ![rising](arrow.png) | 0 | 1 | 0 | `q(n+1)` has the same level as `d` |
   | ![rising](arrow.png) | 1 | 0 | 1 | `q(n+1)` has the same level as `d` |
   | ![rising](arrow.png) | 1 | 1 | 1 | `q(n+1)` has the same level as `d` |

   **JK-type FF**
   | **clk** | **j** | **k** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-: | :-- |
   | ![rising](arrow.png) | 0 | 0 | 0 | 0 | No change |
   | ![rising](arrow.png) | 0 | 0 | 1 | 1 | No change |
   | ![rising](arrow.png) | 0 | 1 | 0 | 0 | Reset |
   | ![rising](arrow.png) | 0 | 1 | 1 | 0 | Reset |
   | ![rising](arrow.png) | 1 | 0 | 0 | 1 | Set |
   | ![rising](arrow.png) | 1 | 0 | 1 | 1 | Set |
   | ![rising](arrow.png) | 1 | 1 | 0 | 1 | Toggle |
   | ![rising](arrow.png) | 1 | 1 | 1 | 0 | Toggle |

   **T-type FF**
   | **clk** | **t** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](arrow.png) | 0 | 0 | 0 | No change |
   | ![rising](arrow.png) | 0 | 1 | 1 | No change |
   | ![rising](arrow.png) | 1 | 0 | 1 | Invert |
   | ![rising](arrow.png) | 1 | 1 | 0 | Invert |
