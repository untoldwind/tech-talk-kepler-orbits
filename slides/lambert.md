
# How to get from A-to-B

Reaching a specific point is generally not that hard. But since everything is in motion it is necessary to reach a specific point at the correct time.
Example:
- Probe launches from earth orbit
- Has to move to mars orbit when mars is also at the same position at arrival

---

## Hohmann transfer

(Walter Hohmann 1925, Konstantin Ziolkowski 1911)
- Can be calculated by just using conservation of energy and angular momentum
- Orbits need to have (nearly) the same plane of motion
- Orbits have to be (nearly) circular

![bg right:45% height:550](./hohmann-transfer.png)

---

## Delta-V

- The propellant of a space-craft/-probe is limited, therefore the total change in velocity ($\Delta v$) is limited as well.
- A good rocket engine should maximize the generated $\Delta v$ per unit of propellant (specific impulse $I_{sp}$). With exception of ion-engine this can only be done using high burn temperatures (or high-pressure chambers). The amount of times such an engine can be started is limited.
- Generally: A transfer with constant acceleration is not feasible, instead a transfer should be done with an acceleration at the beginning, a deceleration at the end and as little correction-burns as possible.

---

## Lambert's problem

(Johann Lambert 1750-1761, solved by Joseph-Louse Lagrange 1772-1793)

Given point $A$ and $B$, find a Kepler-orbit that moves from $A$ to $B$ in time $t$. Thereby calculate the velocities $v_A$ and $v_B$ of that orbit.

As long as $t > 0$ there is at least one solution, though probably not a feasible one.

E.g. get from Earth to Mars in one second.

![bg right:40% height:500](./lambert.svg)

---

## Transfer windows

Decide a start time $t_0$.
$A$ is the position of Earth at that time.
Decide a transfer time $t_T$ from Earth to Mars.
$B$ is the position of Mars at $t_0 + t_T$.
Solve Lambert's problem.
Since velocities of Earth and Mars are also known, the required $\Delta v$ for acceleration and deceleration can be calculated.

![bg right:60% height:700](./earth-mars.png)