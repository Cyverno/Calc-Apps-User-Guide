# CHEM 117 Midterm 1 App: User Guide

The CHEM 117 app puts the Midterm 1 course notes and a set of chemistry tools on your TI-84. This guide shows where everything is in the menus and how to use each tool, with a worked example for each one.

The app has three kinds of things in it:

- **Notes:** the course notes for chapters 1 to 7, page by page, plus constants, unit conversions, study checklists, and a molecular geometry reference.
- **Solvers:** small calculators that ask for the values in a problem and show the answer, such as molar mass, limiting reactant, electron configuration, and VSEPR shape.
- **Shape chart:** the molecular geometry chart. Pick the number of electron groups and lone pairs to see the shape, its bond angles, and its hybridization. On the TI-84 Plus CE each shape is also drawn as a ball-and-stick picture.

Use the solvers to check your own work. A solver only knows what you type in, and it rounds what it shows (see [Reading results](#reading-results)).

## Contents

1. [Start and quit](#1-start-and-quit)
2. [Getting around](#2-getting-around)
3. [Typing in values and reading results](#3-typing-in-values-and-reading-results)
4. [What's where](#4-whats-where)
5. [Menu by menu](#5-menu-by-menu)
   - [Constants](#constants) · [CH1](#ch1-matter) · [CH2](#ch2-atoms-and-the-mole) · [CH3](#ch3-light-and-electrons) · [CH4](#ch4-bonding) · [CH5](#ch5-shapes-and-mo-theory) · [CH6](#ch6-intermolecular-forces) · [CH7](#ch7-stoichiometry) · [Checklists and geometry reference](#checklists-and-geometry-reference)
6. [Unlocking the notes (native version)](#6-unlocking-the-notes-native-version)
7. [Limits](#7-limits)
8. [Troubleshooting](#8-troubleshooting)
9. [Setup: loading the app](#9-setup-loading-the-app)

## 1. Start and quit

### Which version you have

Press **PRGM** and look at the list:

- **`CHEM117`** (with `ZCHEM...` programs under it) is the **BASIC version**. On a color TI-84 Plus CE it has every tool and the full notes. On a black and white TI-84 Plus it has shorter notes and fewer tools.
- **`CHEM117N`** is the **native version** (TI-84 Plus CE only). It has every tool, runs faster, and its notes need a license made for your calculator (see [Unlocking the notes](#6-unlocking-the-notes-native-version)).

Tools that the TI-84 Plus doesn't have are marked **CE only** in this guide. The BASIC CE and native versions have the same menus, so the same key presses work on both.

### Start the app

- **BASIC version:** press **PRGM**, choose **CHEM117**, and press **ENTER** twice. Don't run the `ZCHEM...` programs yourself; `CHEM117` runs them for you.
- **Native version:** run it the way it was set up on your calculator. On OS 5.4 or older that's `Asm(prgmCHEM117N)` from the home screen (`Asm(` is in the CATALOG). On newer OS versions it starts through the arTIfiCE launcher. With a license installed it takes about 3 seconds to open while it checks the license; that pause is normal.

### Quit

- On the main menu choose **MORE►**, then **QUIT**. In the BASIC version this also deletes the temporary lists the app made.
- **BASIC version, stop right away:** press **ON**, then choose **1: Quit**. This works at any point, even in the middle of a solver.

### Exams

Press-to-Test (exam mode) turns off all programs, so the app can't be used during an exam that requires it. This is true of every version.

## 2. Getting around

The main menu is called **CHEM 117 MT1** and has two pages:

- **Page 1:** CONSTANTS and chapters 1 to 5, then **MORE►**.
- **Page 2:** chapters 6 and 7, CHECKLISTS, GEOMETRY REF (CE only), **◄BACK**, and **QUIT**.

Each chapter menu has a **NOTES** item that opens a list of topics, followed by that chapter's tools.

| To do this | BASIC version | Native version |
|---|---|---|
| Choose a menu item | Press its number, or use the arrow keys and press **ENTER** | Same |
| Go back a menu | Choose **◄BACK** | Choose **◄BACK**, or press **CLEAR** |
| Next notes page | **ENTER** | **ENTER** |
| Previous notes page | Not available | **▲** |
| Leave a notes topic | Press **ENTER** past the last page | **CLEAR** on any page, or **ENTER** on the last page |
| Close a results screen | **ENTER** | Any key |
| Move through the shape chart | **◄ ►** or **▲ ▼** (CE only) | **◄ ►** or **▲ ▼** |
| Leave the shape chart | **CLEAR** or **ENTER** (CE); **ENTER** past the last screen (TI-84 Plus) | **CLEAR** or **ENTER** |

Notes pages show the topic title on the top row. In the BASIC version the top row also shows the page number, for example `2/3`. The native version shows `ENTER next  CLEAR back` at the bottom of each page.

**Native version, long topic lists:** the CH4 and CH7 notes lists have 12 topics each. Number keys only go up to 9, so reach topics 10 to 12 with the arrow keys. These two lists have no **◄BACK** item; press **CLEAR** to leave them.

## 3. Typing in values and reading results

### Numbers

| What | How |
|---|---|
| Negative number | Use the **(-)** key at the bottom of the keypad, not the minus key. |
| Scientific notation | Press **2nd**, then the **comma** key (EE). It shows as `E`. For 3.7 × 10⁻¹⁹, type `3.7`, **2nd**, **comma**, **(-)**, `19`. |
| The unknown | In tools that say `0=UNKNOWN` or `(0=?)`, enter **0** for the value you want. The tool fills it in. |
| Skip an optional value | Prompts that say `(0=SKIP)` are optional. Enter **0** to leave them out. |

**BASIC version:** prompts accept anything the calculator can work out, such as `25+273.15` or `2*1.008`. After a molar mass calculation the result is kept in the variable `M`, so you can type **ALPHA**, **M** at a later prompt to use it.

**Native version:** type plain numbers; it doesn't work out expressions. **DEL** or **CLEAR** erases the last character. Pressing **CLEAR** on an empty line enters 0, so there's no way to back out of a solver partway through; finish the prompts and press a key on the results screen to return to the menu.

### Elements

You can enter an element by its symbol or its atomic number.

**BASIC version** asks `SYMBOL OR Z?`:

- Type the symbol with **ALPHA** before each letter: `NA` for sodium. On a CE with lowercase turned on, `Na` works too.
- To type several letters in a row, press **2nd**, **ALPHA** to lock letter mode. Press **ALPHA** again to unlock it.
- Or type the atomic number, such as `11`.
- If the symbol isn't recognized, you'll see `NOT FOUND` and the prompt repeats.

**Native version** asks with a prompt such as `element?`, `atom 1?`, or `central atom?`. These prompts start in letter mode, with `[A]` shown at the bottom of the screen:

- Press the keys for the letters, using the green letter labels above the keys. You don't need ALPHA before each letter, and capital or lowercase doesn't matter.
- To type an atomic number instead, press **ALPHA** once to switch to numbers (`[A]` goes away), then type the number.
- If the symbol isn't recognized, you'll see `not found, try again` and the prompt repeats.
- Press **CLEAR** on an empty line to cancel and go back to the menu.

> **Known issue (native version):** the letter keys for X, Y, and Z are mapped one key off, so you can't type the symbols **Xe, Y, Yb, Zn, or Zr**. Use their atomic numbers instead: Xe 54, Y 39, Yb 70, Zn 30, Zr 40.

### Formulas

Tools that need a formula ask how many different elements it has, then each element and how many of it there are. Count every atom of each element, including the ones inside parentheses.

For Ca(OH)₂: 3 elements, then Ca with count 1, O with count 2, H with count 2.

### Reading results

- **Rounding:** results show 4 significant figures. Molar masses and percent composition show 2 decimal places, and average atomic mass shows 3. Round your final answer to the right number of sig figs for the problem yourself.
- **Scientific notation:** `E` means "times ten to the". `4.087E-19` is 4.087 × 10⁻¹⁹.
- **Trailing zeros:** the BASIC version drops trailing zeros, so 4.960 shows as `4.96`.
- **Units:** each tool uses the units in its prompts, such as nm, Hz, J, kJ/mol, g, g/mol, kg, and m/s. Convert first if your problem gives something else. Mass in the physics formulas (de Broglie, Heisenberg, electron speed) is in **kg**.
- **Subscripts and superscripts** are written on one line: `[Ar]4s2 3d6` means [Ar]4s²3d⁶, and `C6H12O6` means C₆H₁₂O₆.

## 4. What's where

### Find a tool fast

The keys column is what to press from the main menu on a TI-84 Plus CE (BASIC or native). On the TI-84 Plus some numbers are different, so go by what's on the screen.

| To do this | Go to | Keys (CE) |
|---|---|---|
| Look up a constant (N_A, h, c, electron mass) | CONSTANTS ► CONSTANTS | 1, 1 |
| Look up a unit conversion (nm, pm, L, J, °C/°F/K) | CONSTANTS ► CONVERSIONS | 1, 2 |
| [Convert a temperature](#temperature-converter) (CE only) | CONSTANTS ► TEMP CONVERTER | 1, 4 |
| [Classify a substance](#classify-help) (CE only) | CH1 ► CLASSIFY HELP | 2, 2 |
| [Count sig figs](#count-sig-figs) (CE only) | CH1 ► COUNT SIG FIGS | 2, 3 |
| [Round to sig figs](#round-to-sig-figs) (CE only) | CH1 ► ROUND TO SF | 2, 4 |
| [Find density, mass, or volume](#density) (CE only) | CH1 ► DENSITY d=m/V | 2, 5 |
| [Count protons, neutrons, electrons](#protons-neutrons-electrons) (CE only) | CH2 ► p/n/e- COUNT | 3, 2 |
| [Average atomic mass from isotopes](#average-atomic-mass-from-abundances) (CE only) | CH2 ► AVG MASS/ISO % ► AVG FROM % | 3, 3, 1 |
| [Isotope % from the average mass](#isotope-percentages-from-the-average-mass) | CH2 ► AVG MASS/ISO % ► % FROM AVG | 3, 3, 2 |
| [Molar mass and mass percent](#molar-mass-and-percent-composition) | CH2 ► MOLAR MASS/% | 3, 4 |
| [Convert grams, moles, particles](#grams-moles-and-particles) | CH2 ► g/mol/PARTICLE | 3, 5 |
| [Find a nuclear decay product](#nuclear-decay-product) (CE only) | CH2 ► NUCLEAR EQN ► DECAY PRODUCT | 3, 6, 1 |
| [Find the missing particle](#missing-particle-in-a-nuclear-equation) (CE only) | CH2 ► NUCLEAR EQN ► FIND MISSING | 3, 6, 2 |
| [Wavelength, frequency, photon energy](#light-wavelength-frequency-energy) | CH3 ► LIGHT λ/f/E | 4, 2 |
| [Photoelectric effect](#photoelectric-effect) | CH3 ► PHOTOELECTRIC | 4, 3 |
| [Hydrogen atom transitions](#bohr-hydrogen-atom) | CH3 ► BOHR H ATOM | 4, 4 |
| [de Broglie wavelength](#de-broglie-wavelength) (CE only) | CH3 ► e- WAVES ► DE BROGLIE | 4, 5, 1 |
| [Heisenberg uncertainty](#heisenberg-uncertainty) (CE only) | CH3 ► e- WAVES ► HEISENBERG | 4, 5, 2 |
| [Electron configuration](#electron-configuration) | CH3 ► e- CONFIG/QN ► e- CONFIG | 4, 6, 1 |
| [Check a set of quantum numbers](#quantum-number-check) (CE only) | CH3 ► e- CONFIG/QN ► CHECK QUANT #S | 4, 6, 2 |
| [Subshells and electrons in a shell](#shell-information) (CE only) | CH3 ► e- CONFIG/QN ► SHELL n INFO | 4, 6, 3 |
| [Bond type from electronegativity](#bond-type-from-electronegativity-difference) (CE only) | CH4 ► ΔEN BOND TYPE | 5, 2 |
| [Formula of an ionic compound](#ionic-formula) (CE only) | CH4 ► IONIC FORMULA | 5, 3 |
| [Roman numeral for a metal](#roman-numeral-metal-charge) (CE only) | CH4 ► ROMAN NUMERAL | 5, 4 |
| [Total valence electrons for a Lewis structure](#total-valence-electrons) (CE only) | CH4 ► VALENCE e- | 5, 5 |
| [Formal charge](#formal-charge) (CE only) | CH4 ► FORMAL CHARGE | 5, 6 |
| [Shape, angle, hybridization of a molecule](#vsepr-solver) | CH5 ► VSEPR SOLVER | 6, 2 |
| [Shape from electron groups and lone pairs](#shape-chart) | CH5 ► SHAPE CHART | 6, 3 |
| [MO diagram and bond order](#mo-diagram-for-a-diatomic) (CE only) | CH5 ► MO DIATOMIC | 6, 4 |
| [Count σ and π bonds](#sigma-and-pi-bond-count) (CE only) | CH5 ► σ/π BOND COUNT | 6, 5 |
| [Strongest intermolecular force](#imf-wizard) (CE only) | MORE► ► CH6 ► IMF WIZARD | 7, 1, 5 |
| [Balance an equation](#balance-an-equation) | MORE► ► CH7 ► BALANCE EQN | 7, 2, 2 |
| [Grams of A to grams of B](#mass-to-mass) | MORE► ► CH7 ► MASS►MASS | 7, 2, 3 |
| [Limiting reactant, theoretical and % yield](#limiting-reactant-and-yield) | MORE► ► CH7 ► LIMITING/YIELD ► LIMITING | 7, 2, 4, 1 |
| [Percent yield only](#percent-yield-only) (CE only) | MORE► ► CH7 ► LIMITING/YIELD ► % YIELD ONLY | 7, 2, 4, 2 |
| [Empirical and molecular formula](#empirical-and-molecular-formula-from-grams-or-percent) | MORE► ► CH7 ► EMPIRICAL/COMB ► MASS OR % | 7, 2, 5, 1 |
| [Formula from combustion data](#empirical-formula-from-combustion-data) | MORE► ► CH7 ► EMPIRICAL/COMB ► COMBUSTION | 7, 2, 5, 2 |
| Study checklists | MORE► ► CHECKLISTS | 7, 3 |
| [Geometry reference](#checklists-and-geometry-reference) (CE only) | CH5 ► GEOMETRY REF, or MORE► ► GEOMETRY REF | 6, 6 or 7, 4 |

### Map of the app

Items marked **\*** are CE only.

```
CHEM 117 MT1, page 1
  1 CONSTANTS ....... constants, conversions, light/color notes; TEMP CONVERTER *
  2 CH1 MATTER ...... notes; CLASSIFY HELP *, COUNT SIG FIGS *, ROUND TO SF *, DENSITY *
  3 CH2 ATOMS/MOLE .. notes; p/n/e- COUNT *, AVG MASS/ISO %, MOLAR MASS/%,
                      g/mol/PARTICLE, NUCLEAR EQN *
  4 CH3 LIGHT/e- .... notes; LIGHT, PHOTOELECTRIC, BOHR H ATOM, e- WAVES *, e- CONFIG/QN
  5 CH4 BONDING ..... notes; ΔEN BOND TYPE *, IONIC FORMULA *, ROMAN NUMERAL *,
                      VALENCE e- *, FORMAL CHARGE *
  6 CH5 SHAPES/MO ... notes; VSEPR SOLVER, SHAPE CHART, MO DIATOMIC *, σ/π BOND COUNT *,
                      GEOMETRY REF *
  7 MORE►

CHEM 117 MT1, page 2
  1 CH6 IMF ......... forces, boiling point, solubility, phases notes; IMF WIZARD *
  2 CH7 STOICH ...... notes; BALANCE EQN, MASS►MASS, LIMITING/YIELD, EMPIRICAL/COMB,
                      MOLAR MASS/%
  3 CHECKLISTS
  4 GEOMETRY REF *
    ◄BACK
    QUIT
```

## 5. Menu by menu

Each chapter below starts with its menu as it appears on the screen, then its notes topics, then each tool: where it is, what it asks for, what it shows, and a worked example. Prompts are described in plain words; the exact wording differs a little between versions.

### Constants

**Main menu ► 1 CONSTANTS**

| # | TI-84 Plus CE | TI-84 Plus |
|:-:|---|---|
| 1 | CONSTANTS | CONSTANTS |
| 2 | CONVERSIONS | CONVERSIONS |
| 3 | LIGHT/COLOR | LIGHT/COLOR |
| 4 | TEMP CONVERTER | ◄BACK |
| 5 | ◄BACK | |

**Notes:** the course constants (N_A, h, c, hc, electron mass, 1 u in kg, the Bohr energy constant), unit conversions (nm, pm, cm, kg, L, J, temperature formulas), and the visible light range and color order.

#### Temperature converter

**CE only.**

- **Where:** CONSTANTS ► TEMP CONVERTER
- **Asks:** the unit you're converting from (°C, °F, or K), then the value.
- **Shows:** the temperature in °C, °F, and K.
- **Example:** from °C, `25` gives 77 °F and 298.2 K.

### CH1: Matter

**Main menu ► 2 CH1 MATTER**

| # | TI-84 Plus CE | TI-84 Plus |
|:-:|---|---|
| 1 | NOTES | Opens the notes list directly |
| 2 | CLASSIFY HELP | |
| 3 | COUNT SIG FIGS | |
| 4 | ROUND TO SF | |
| 5 | DENSITY d=m/V | |
| 6 | ◄BACK | |

**Notes:** matter types, physical and chemical properties, states of matter, sig fig rules.

#### Classify help

**CE only.**

- **Where:** CH1 ► CLASSIFY HELP
- **Asks:** yes or no questions. Can it be separated physically? If yes: is the mixture uniform? If no: can it be broken down chemically?
- **Shows:** element, compound, homogeneous mixture (solution), or heterogeneous mixture.
- **Example:** salt water. Separable physically: YES. Uniform: YES. Result: HOMOGENEOUS (SOLUTION).

#### Count sig figs

**CE only.**

- **Where:** CH1 ► COUNT SIG FIGS
- **Asks:** the number, typed exactly as written. Keep trailing zeros and the decimal point; they matter.
- **Shows:** the number of significant figures.
- **Examples:** `0.00500` has 3. `1200` has 2. `1200.` has 4. `6.022E23` has 4.

#### Round to sig figs

**CE only.**

- **Where:** CH1 ► ROUND TO SF
- **Asks:** the number, then how many sig figs you want.
- **Shows:** the rounded number and the same value in scientific notation.
- **Example:** `1199.7` to 3 sig figs gives 1.20E3.

#### Density

**CE only.**

- **Where:** CH1 ► DENSITY d=m/V
- **Asks:** mass, volume, and density. Enter 0 for the one you want.
- **Shows:** all three. Units follow what you typed (grams and mL give g/mL).
- **Example:** mass `10`, volume `0`, density `2.5` gives V = 4.

### CH2: Atoms and the mole

**Main menu ► 3 CH2 ATOMS/MOLE**

| # | TI-84 Plus CE | TI-84 Plus |
|:-:|---|---|
| 1 | NOTES | NOTES |
| 2 | p/n/e- COUNT | ISOTOPE % CALC |
| 3 | AVG MASS/ISO % | MOLAR MASS/% |
| 4 | MOLAR MASS/% | g/mol/PARTICLE |
| 5 | g/mol/PARTICLE | ◄BACK |
| 6 | NUCLEAR EQN | |
| 7 | ◄BACK | |

**Notes:** nuclide symbols, average atomic mass, the mole, nuclear equations, the periodic table, ion charges.

#### Protons, neutrons, electrons

**CE only.**

- **Where:** CH2 ► p/n/e- COUNT
- **Asks:** the element, its mass number A, and its charge.
- **Shows:** protons, neutrons, and electrons, whether it's a cation, anion, or neutral atom, and the periodic table's average mass for that element.
- **Example:** Fe, `56`, `3` (Fe³⁺) gives 26 protons, 30 neutrons, 23 electrons.

#### Average atomic mass from abundances

**CE only.**

- **Where:** CH2 ► AVG MASS/ISO % ► AVG FROM %
- **Asks:** how many isotopes, then each isotope's mass and abundance. Give abundances as percents or as decimals, but use the same kind for all of them.
- **Shows:** the average atomic mass and the sum of the abundances, which should be 1 or 100. If it isn't, check your typing.
- **Example:** chlorine, 2 isotopes: `34.969` at `75.78`, and `36.966` at `24.22`. Average mass 35.453.

#### Isotope percentages from the average mass

- **Where:** CH2 ► AVG MASS/ISO % ► % FROM AVG. On the TI-84 Plus: CH2 ► ISOTOPE % CALC.
- **Asks:** the average atomic mass, then the masses of the two isotopes.
- **Shows:** the percent abundance of each isotope.
- **Example:** copper: average `63.546`, mass 1 `62.9296`, mass 2 `64.9278`. Results: 69.15% and 30.85%.

#### Molar mass and percent composition

- **Where:** CH2 ► MOLAR MASS/%. The same tool is also in CH7 ► MOLAR MASS/%.
- **Asks:** the formula, element by element (see [Formulas](#formulas)).
- **Shows:** the molar mass in g/mol and the mass percent of each element.
- **Example:** H₂O: 2 elements, H with count 2, O with count 1. Molar mass 18.02 g/mol; H 11.19%, O 88.81%.

#### Grams, moles, and particles

- **Where:** CH2 ► g/mol/PARTICLE
- **Asks:** the molar mass (enter 0 to work it out from the formula), then which amount you know (grams, moles, or particles) and its value.
- **Shows:** molar mass, grams, moles, and number of particles.
- **Example:** water, molar mass `18.02`, you know grams: `36.04`. Results: 2 mol, 1.204E24 molecules.
- **Tip:** the particle count is molecules (or formula units). For the atoms of one element, multiply by that element's subscript.

#### Nuclear decay product

**CE only.**

- **Where:** CH2 ► NUCLEAR EQN ► DECAY PRODUCT
- **Asks:** the parent element, its mass number, and the decay type (alpha, beta, positron, gamma, or neutron loss).
- **Shows:** the product nuclide with its Z, A, and neutron count.
- **Examples:** U, `238`, alpha gives Th-234. C, `14`, beta gives N-14.

#### Missing particle in a nuclear equation

**CE only.**

- **Where:** CH2 ► NUCLEAR EQN ► FIND MISSING
- **Asks:** the total mass number A and total atomic number Z on the left side, then on the right side, counting only the pieces you know.
- **Shows:** the missing piece's A and Z, and its name when it's a common particle (alpha, beta, positron, gamma, neutron, or proton).
- **Example:** U-238 → Th-234 + ?. Left A `238`, left Z `92`, right A `234`, right Z `90`. Missing: A = 4, Z = 2, ALPHA (He-4).

### CH3: Light and electrons

**Main menu ► 4 CH3 LIGHT/e-**

| # | TI-84 Plus CE | TI-84 Plus |
|:-:|---|---|
| 1 | NOTES | NOTES |
| 2 | LIGHT λ/f/E | LIGHT λ/f/E |
| 3 | PHOTOELECTRIC | PHOTOELECTRIC |
| 4 | BOHR H ATOM | BOHR H ATOM |
| 5 | e- WAVES | e- CONFIG |
| 6 | e- CONFIG/QN | ◄BACK |
| 7 | ◄BACK | |

**Notes:** light, the photoelectric effect, Bohr hydrogen levels, electron waves, quantum numbers, electron configuration, and (under **MORE►** in the BASIC version) periodic trends and electronegativity values.

#### Light: wavelength, frequency, energy

- **Where:** CH3 ► LIGHT λ/f/E
- **Asks:** which value you know (λ in nm, frequency in Hz, energy per photon in J, or energy in kJ/mol), then the value.
- **Shows:** λ in m and nm, frequency, energy per photon in J, and energy in kJ/mol. On the CE it also names the region of the spectrum and, for visible light, the color.
- **Example:** λ = `486.1` nm gives f = 6.167E14 Hz, E = 4.087E-19 J, 246.1 kJ/mol, VISIBLE, BLUE.

#### Photoelectric effect

- **Where:** CH3 ► PHOTOELECTRIC
- **Asks:** how the work function Φ is given (Φ in J, Φ in kJ/mol, threshold λ₀ in nm, or threshold f₀ in Hz) and its value. Then the photon's wavelength in nm; enter 0 there to give its frequency in Hz instead.
- **Shows:** the photon energy, Φ in J, the threshold λ₀ and f₀, and, if an electron is ejected, its kinetic energy and speed. If the photon energy is less than Φ, it says no electron is ejected.
- **Example:** Φ = `3.7E-19` J, photon `400` nm. Photon energy 4.966E-19 J, λ₀ = 536.8 nm, KE = 1.266E-19 J, speed 5.273E5 m/s.

#### Bohr hydrogen atom

- **Where:** CH3 ► BOHR H ATOM
- **Asks:** n initial and n final. Enter 0 for n final to get the energy of one level.
- **Shows:** the energies of both levels, ΔE, the photon's wavelength and frequency, whether a photon is emitted or absorbed, and the series (Lyman, Balmer, Paschen, Brackett, or Pfund and beyond).
- **Example:** n = `3` to n = `2`. ΔE = -3.025E-19 J, λ = 656.5 nm, f = 4.565E14 Hz, EMITS PHOTON, BALMER (VISIBLE).
- **One level:** n initial `2`, n final `0` gives Eₙ = -5.445E-19 J.

#### de Broglie wavelength

**CE only.**

- **Where:** CH3 ► e- WAVES ► DE BROGLIE
- **Asks:** mass in kg, speed in m/s, and wavelength in m. Enter 0 for the unknown.
- **Shows:** all three, with λ also in nm.
- **Example:** an electron, `9.109E-31` kg, at `2.2E6` m/s, λ `0`. λ = 3.306E-10 m (0.3306 nm).

#### Heisenberg uncertainty

**CE only.**

- **Where:** CH3 ► e- WAVES ► HEISENBERG
- **Asks:** mass in kg, Δx in m, and Δv in m/s. Enter 0 for the unknown.
- **Shows:** the minimum value of the unknown.
- **Example:** an electron, `9.109E-31` kg, Δx = `1E-10` m, Δv `0`. Δv is at least 5.789E5 m/s.

#### Electron configuration

- **Where:** CH3 ► e- CONFIG/QN ► e- CONFIG. On the TI-84 Plus: CH3 ► e- CONFIG.
- **Asks:** the element, then its charge. Enter 0 for a neutral atom, a positive number for a cation, and a negative number for an anion.
- **Shows:** the condensed (noble gas) configuration, the full configuration, the total and unpaired electrons, and whether it's diamagnetic or paramagnetic. It also shows valence electrons for main group elements, or notes a transition metal. Press **ENTER** (BASIC) or any key (native) to move between screens.
- **Examples:** Fe, `0`: [Ar]4s2 3d6, 4 unpaired, PARAMAGNETIC. Fe, `3`: [Ar]3d5. Cl, `-1`: [Ne]3s2 3p6.
- **Exceptions handled:** Cr, Cu, Mo, Ag, and Au (the ones in the notes).

#### Quantum number check

**CE only.**

- **Where:** CH3 ► e- CONFIG/QN ► CHECK QUANT #S
- **Asks:** n, l, mₗ, and mₛ. Enter 0 for mₛ to skip it.
- **Shows:** whether the set is valid and, if not, which rule it breaks. For a valid set it names the subshell.
- **Examples:** `3`, `2`, `-2`, `.5` is valid: 3d. `2`, `2`, `0`, `0` is invalid, because l must be 0 to n-1.

#### Shell information

**CE only.**

- **Where:** CH3 ► e- CONFIG/QN ► SHELL n INFO
- **Asks:** the shell number n.
- **Shows:** the number of subshells, orbitals (n²), and maximum electrons (2n²). The BASIC version also lists the allowed l values and the subshell names.
- **Example:** n = `3`: 3 subshells (3s, 3p, 3d), 9 orbitals, 18 electrons.

### CH4: Bonding

**Main menu ► 5 CH4 BONDING**

| # | TI-84 Plus CE | TI-84 Plus |
|:-:|---|---|
| 1 | NOTES | Opens the notes list directly |
| 2 | ΔEN BOND TYPE | |
| 3 | IONIC FORMULA | |
| 4 | ROMAN NUMERAL | |
| 5 | VALENCE e- | |
| 6 | FORMAL CHARGE | |
| 7 | ◄BACK | |

**Notes:** bond type by ΔEN, Roman numeral cations, -ide anions, -ate and -ite ions, polyatomic ions, naming ionic compounds, naming molecular compounds, naming acids, Lewis structure steps, formal charge, resonance, and (CE only) the octet rule and bonds. In the BASIC version the list is split over two pages; choose **MORE►** for the second.

#### Bond type from electronegativity difference

**CE only.**

- **Where:** CH4 ► ΔEN BOND TYPE
- **Asks:** the two atoms. It asks for an electronegativity value only if an element isn't in its table.
- **Shows:** each atom's electronegativity, ΔEN, the bond type (nonpolar covalent, polar covalent, or ionic), and which atom is the δ- end.
- **Examples:** Na and Cl: ΔEN = 2.23, IONIC. O and H: POLAR COVALENT, δ- end O.

#### Ionic formula

**CE only.**

- **Where:** CH4 ► IONIC FORMULA
- **Asks:** the cation's charge and the anion's charge. The signs don't matter here.
- **Shows:** the subscript for the cation and for the anion (the criss-cross method, reduced).
- **Example:** Al³⁺ and O²⁻: `3`, `-2`. Cation subscript 2, anion subscript 3: Al₂O₃.

#### Roman numeral (metal charge)

**CE only.**

- **Where:** CH4 ► ROMAN NUMERAL
- **Asks:** the number of metal atoms, the anion's charge **with its minus sign**, and the number of anions.
- **Shows:** the metal's charge and its Roman numeral.
- **Example:** Fe₂O₃: `2`, `-2`, `3`. Metal charge +3: iron(III).

#### Total valence electrons

**CE only.**

- **Where:** CH4 ► VALENCE e-
- **Asks:** the formula, element by element, then the overall charge.
- **Shows:** the total valence electrons and electron pairs for the Lewis structure, with a warning if the count is odd (a radical).
- **Example:** CO₃²⁻: 2 elements, C with count 1, O with count 3, charge `-2`. 24 electrons, 12 pairs.

#### Formal charge

**CE only.**

- **Where:** CH4 ► FORMAL CHARGE
- **Asks:** the atom, the number of lone pair **electrons** on it (count electrons, not pairs), and the number of bonds to it (a double bond counts as 2).
- **Shows:** the formal charge, using FC = valence e- minus (lone pair e- plus bonds).
- **Example:** N in NH₄⁺: N, `0`, `4`. Formal charge +1.

### CH5: Shapes and MO theory

**Main menu ► 6 CH5 SHAPES/MO**

| # | TI-84 Plus CE | TI-84 Plus |
|:-:|---|---|
| 1 | NOTES | NOTES |
| 2 | VSEPR SOLVER | VSEPR SOLVER |
| 3 | SHAPE CHART | SHAPE CHART |
| 4 | MO DIATOMIC | ◄BACK |
| 5 | σ/π BOND COUNT | |
| 6 | GEOMETRY REF | |
| 7 | ◄BACK | |

**Notes:** the SN and VSEPR table, hybridization with σ and π bonds, polarity, chirality, MO theory. The longer geometry reference is item 6 (see [below](#checklists-and-geometry-reference)).

#### VSEPR solver

- **Where:** CH5 ► VSEPR SOLVER
- **Asks:** the central atom, how many **kinds** of outer atoms there are, each kind of outer atom with how many of it, and the overall charge.
- **Shows:** valence electrons, bonded atoms, lone pairs on the central atom, steric number, electron geometry, molecular shape with its bond angles, hybridization, and polarity. The BASIC CE version also counts the electrons around the central atom and points out when it needs double bonds, when an incomplete octet is fine (Be, B), and when it has an expanded octet.
- **How it works:** it follows the Lewis structure steps from the notes. It places single bonds first, fills the outer atoms, and puts leftover electrons on the central atom.
- **Examples:**
  - SO₂: central S, 1 kind, O with count 2, charge `0`. BENT, <120 (~117), sp2, POLAR.
  - CH₂O: central C, 2 kinds, H with count 2 and O with count 1, charge `0`. TRIG PLANAR, 120, POLAR.
  - XeF₄: central Xe, 1 kind, F with count 4, charge `0`. SQUARE PLANAR, sp3d2, NONPOLAR. (On the native version, enter Xe as `54`.)
  - NO₃⁻: central N, 1 kind, O with count 3, charge `-1`. TRIG PLANAR, NONPOLAR.

#### Shape chart

- **Where:** CH5 ► SHAPE CHART. The BASIC CE version also has it on the second page of the geometry reference (GEOMETRY REF ► MORE►).
- **Use it when** you already know the electron groups and lone pairs on the central atom and want the shape, angles, and hybridization. To start from a formula instead, use the [VSEPR solver](#vsepr-solver).
- **Asks:** the number of electron groups around the central atom (2 to 6), then how many of those groups are lone pairs.
- **Shows:** that row of the chart: the electron pair arrangement, the molecular shape, the approximate bond angles, and the hybridization.
  - **TI-84 Plus CE (BASIC and native):** the shape is also drawn as a ball-and-stick picture, with the central atom in orange, the outer atoms in green, and each lone pair as a blue lobe with its two electrons. The row number (for example `5/13`) is at the top right. Press **◄** or **►** (or **▲ ▼**) for the previous or next row; the chart wraps around at the ends. Press **CLEAR** or **ENTER** to go back.
  - **TI-84 Plus:** two text screens with the steric number, bonded atoms and lone pairs, electron geometry, shape and angles, then the hybridization and the polarity (assuming all the outer atoms are the same). No picture.
- **Example:** 4 groups, 1 lone pair: TETRAHEDRAL arrangement, TRIG PYRAMIDAL shape, bond angles <109.5 (~107), sp3. Press **►** for 4 groups and 2 lone pairs: BENT, <109.5 (~104.5).
- **Speed:** the BASIC CE version shows the text right away and takes about 4 seconds to finish each picture. The native version draws instantly.
- **Lone pairs allowed:** 0 for 2 groups, 0 or 1 for 3 groups, 0 to 2 for 4 groups, 0 to 3 for 5 groups, and 0 to 2 for 6 groups. Anything else shows NOT IN THE CHART.

The whole chart:

| Groups | Lone pairs | Arrangement | Shape | Bond angles | Hybrid |
|:-:|:-:|---|---|---|---|
| 2 | 0 | Linear | Linear | 180° | sp |
| 3 | 0 | Trigonal planar | Trigonal planar | 120° | sp2 |
| 3 | 1 | Trigonal planar | Bent | <120° (~117°) | sp2 |
| 4 | 0 | Tetrahedral | Tetrahedral | 109.5° | sp3 |
| 4 | 1 | Tetrahedral | Trigonal pyramidal | <109.5° (~107°) | sp3 |
| 4 | 2 | Tetrahedral | Bent | <109.5° (~104.5°) | sp3 |
| 5 | 0 | Trigonal bipyramidal | Trigonal bipyramidal | 90°, 120°, 180° | sp3d |
| 5 | 1 | Trigonal bipyramidal | Seesaw | <90°, <120° | sp3d |
| 5 | 2 | Trigonal bipyramidal | T-shaped | <90° | sp3d |
| 5 | 3 | Trigonal bipyramidal | Linear | 180° | sp3d |
| 6 | 0 | Octahedral | Octahedral | 90°, 180° | sp3d2 |
| 6 | 1 | Octahedral | Square pyramidal | <90° | sp3d2 |
| 6 | 2 | Octahedral | Square planar | 90° | sp3d2 |

The VSEPR solver uses the same chart, so a molecule with that many groups and lone pairs gets the same shape and angles there.

#### MO diagram for a diatomic

**CE only.**

- **Where:** CH5 ► MO DIATOMIC
- **Asks:** atom 1, atom 2, and the charge.
- **Shows:** the MO configuration, bond order, unpaired electrons, and whether it's diamagnetic or paramagnetic. A bond order of 0 or less is flagged as not stable.
- **Examples:** O₂: bond order 2, 2 unpaired, PARAMAGNETIC. N₂: bond order 3, DIAMAGNETIC. O₂⁺ (charge `1`): bond order 2.5. He₂: bond order 0, not stable.
- **Limit:** two atoms from H and He, or two from Li through Ne. Mixed pairs such as CO and NO work.

#### Sigma and pi bond count

**CE only.**

- **Where:** CH5 ► σ/π BOND COUNT
- **Asks:** the number of single, double, and triple bonds.
- **Shows:** the number of σ and π bonds. A single bond is 1 σ, a double bond is 1 σ + 1 π, and a triple bond is 1 σ + 2 π.
- **Example:** CH₂O has 2 single bonds and 1 double bond: `2`, `1`, `0`. 3 σ, 1 π.

### CH6: Intermolecular forces

**Main menu ► 7 MORE► ► 1 CH6 IMF**

| # | TI-84 Plus CE | TI-84 Plus |
|:-:|---|---|
| 1 | FORCES RANKED | FORCES RANKED |
| 2 | BOILING POINT | BOILING POINT |
| 3 | SOLUBILITY | SOLUBILITY |
| 4 | PHASES+WATER | PHASES+WATER |
| 5 | IMF WIZARD | ◄BACK |
| 6 | ◄BACK | |

**Notes:** items 1 to 4 open the notes topics directly: the forces ranked by strength, boiling point trends, solubility, and phases and water.

#### IMF wizard

**CE only.**

- **Where:** CH6 ► IMF WIZARD
- **Asks:** yes or no questions. Are ions present? Is there H bonded to N, O, or F? Is the molecule polar?
- **Shows:** the strongest intermolecular force: ion-dipole or ionic, hydrogen bonding, dipole-dipole, or London dispersion only.
- **Example:** water. Ions: NO. H on N, O, or F: YES. Result: HYDROGEN BONDING.

### CH7: Stoichiometry

**Main menu ► 7 MORE► ► 2 CH7 STOICH** (the same on both calculators)

| # | Item |
|:-:|---|
| 1 | NOTES |
| 2 | BALANCE EQN |
| 3 | MASS►MASS |
| 4 | LIMITING/YIELD |
| 5 | EMPIRICAL/COMB |
| 6 | MOLAR MASS/% (the same tool as in [CH2](#molar-mass-and-percent-composition)) |
| 7 | ◄BACK |

**Notes:** the core idea, reaction types, balancing, mole ratios, limiting reactant, yield, % composition, empirical formula, molecular formula, combustion analysis, units and checks, and common molar masses. In the BASIC version the list is split over two pages; choose **MORE►** for the second.

#### Balance an equation

- **Where:** CH7 ► BALANCE EQN
- **Before you start:** list the elements in the equation in any order, and keep that order for every formula.
- **Asks:** the number of elements, the number of reactants, the number of products, and then each formula's atom counts in your element order, reactants first.
  - **BASIC version:** type each formula's counts as a list in curly braces. **2nd**, **(** gives `{` and **2nd**, **)** gives `}`.
  - **Native version:** type the counts one at a time. A prompt like `R1 el2` means reactant 1, element 2; `P2 el1` means product 2, element 1.
- **Shows:** the coefficients, labeled R1, R2, ... for reactants and P1, P2, ... for products.
- **Example:** C₃H₈ + O₂ → CO₂ + H₂O with elements in the order C, H, O. 3 elements, 2 reactants, 2 products.

  | Formula | BASIC list | Native, one at a time |
  |---|---|---|
  | C₃H₈ | `{3,8,0}` | 3, 8, 0 |
  | O₂ | `{0,0,2}` | 0, 0, 2 |
  | CO₂ | `{1,0,2}` | 1, 0, 2 |
  | H₂O | `{0,2,1}` | 0, 2, 1 |

  Coefficients: R1 = 1, R2 = 5, P1 = 3, P2 = 4. So C₃H₈ + 5 O₂ → 3 CO₂ + 4 H₂O.
- If you see **CAN'T BALANCE**, check the counts and the element order.

#### Mass to mass

- **Where:** CH7 ► MASS►MASS
- **Asks:** for a reaction where a A → b B: grams of A, the molar mass of A, the coefficient of A, the coefficient of B, and the molar mass of B.
  - **BASIC version:** enter 0 for a molar mass to work it out from the formula on the spot.
  - **Native version:** type the molar masses. Use MOLAR MASS/% first if you need them.
- **Shows:** moles of A, moles of B, grams of B, and number of B particles.
- **Example:** grams of water from 10.0 g of H₂ in 2 H₂ + O₂ → 2 H₂O. Grams `10.0`, M(A) `2.016`, coef A `2`, coef B `2`, M(B) `18.02`. Results: 4.96 mol H₂, 4.96 mol H₂O, 89.38 g H₂O, 2.987E24 molecules.

#### Limiting reactant and yield

- **Where:** CH7 ► LIMITING/YIELD ► LIMITING. On the TI-84 Plus, LIMITING/YIELD goes straight to this tool.
- **Asks:** for a reaction where a A + b B → c C: grams of A, molar mass of A, coefficient of A, grams of B, molar mass of B, coefficient of B, coefficient of C, molar mass of C, and the actual grams of C made (0 to skip). Molar masses work the same way as in mass to mass.
- **Shows:** which reactant is limiting (A, B, or BOTH), moles of C, grams of C (the theoretical yield), grams of the excess reactant left over, and the percent yield if you entered the actual yield.
- **Example:** 4.0 g H₂ and 16.0 g O₂ react to make water, and 15.0 g of water is collected. Enter `4.0`, `2.016`, `2`, `16.0`, `32.00`, `1`, `2`, `18.02`, `15.0`. Results: LIMITING: B (the O₂), 1 mol and 18.02 g of water, 1.984 g of H₂ left over, 83.24% yield.

#### Percent yield only

**CE only.** On the TI-84 Plus, use the limiting reactant tool and enter the actual yield.

- **Where:** CH7 ► LIMITING/YIELD ► % YIELD ONLY
- **Asks:** actual yield, theoretical yield, and percent yield. Enter 0 for the unknown.
- **Shows:** all three. A yield over 100% is flagged as a likely error (a wet or impure product).
- **Example:** actual `15`, theoretical `18.02`, percent `0`. 83.24%.

#### Empirical and molecular formula from grams or percent

- **Where:** CH7 ► EMPIRICAL/COMB ► MASS OR %
- **Asks:** the number of elements, then each element with its grams or its percent. Then the compound's molar mass if you know it (0 to skip).
- **Shows:** the empirical formula and, with a molar mass, the empirical formula mass, the multiplier n, and the molecular formula. The BASIC version also shows the mole ratio.
- **Examples:**
  - Glucose: 3 elements, C `40.0`, H `6.71`, O `53.3`, molar mass `180.16`. Empirical CH2O, n = 6, molecular C6H12O6.
  - Iron oxide: 2 elements, Fe `69.94`, O `30.06`, molar mass `0`. Empirical Fe2O3.
- If the BASIC version shows **NOT CLEAN: CHECK**, the ratio didn't come out close to whole numbers. Check your inputs. The native version doesn't show this warning, so check that the formula it gives makes sense.

#### Empirical formula from combustion data

- **Where:** CH7 ► EMPIRICAL/COMB ► COMBUSTION
- **Asks:** the mass of the sample burned, grams of CO₂ made, grams of H₂O made, and the molar mass (0 to skip). This is for compounds of C and H, with or without O.
- **Shows:** the empirical formula and, with a molar mass, the molecular formula. On the CE it also shows moles of C and H and the grams of O found by difference.
- **Example:** a `0.255` g sample gives `0.561` g CO₂ and `0.306` g H₂O. Empirical formula C3H8O.

### Checklists and geometry reference

**Checklists** (main menu ► 7 MORE► ► 3 CHECKLISTS) is one notes topic: step-by-step checklists for the common problem types, such as photon energy, Lewis structure to polarity, naming, ranking intermolecular forces, and stoichiometry.

**Geometry reference** is CE only. Open it from CH5 ► GEOMETRY REF, or from the main menu with MORE► ► GEOMETRY REF. Its topics are: terms, SN 2 and SN 3, SN 4 (tetrahedral), SN 5 (trigonal bipyramidal), SN 6 (octahedral), hybridization, shape and polarity, Lewis structures for each SN, and common mistakes. In the BASIC version they're split over two pages, and the second page also has shortcuts to the VSEPR SOLVER and the SHAPE CHART.

## 6. Unlocking the notes (native version)

In the native version the solvers and the shape chart are free, and the notes unlock with a license made for your calculator. If your calculator was set up for you with a license, the notes already open and you can skip this.

1. Open any notes topic, for example **MORE►** then **CHECKLISTS**. You'll see a **NOTES LOCKED** screen showing this calculator's ID, which looks like `1A2B 3C4D 5E6F 7081-9C`.
2. Copy the whole ID exactly, including the two characters after the dash. Those two are a check code that catches typos.
3. Send the ID to the person who set up your calculator.
4. They'll send back or load a file named `CHEMLIC.8xv`. Once it's on the calculator, quit the app and start it again, and the notes open.

A license only works on the calculator it was made for. It won't unlock the notes on anyone else's calculator, and someone else's license won't work on yours.

## 7. Limits

- **Electron configuration:** the exceptions handled are Cr, Cu, Mo, Ag, and Au.
- **MO diagrams:** two atoms from H and He, or two from Li through Ne.
- **VSEPR:** one central atom with outer atoms around it. Single bonds are placed first, following the Lewis steps from the notes.
- **Balancing:** 2 to 7 formulas, and up to 7 elements in the native version.
- **Formulas (native):** up to 10 elements in molar mass, valence electron, and empirical formula entries, and up to 8 isotopes or kinds of outer atom.
- **Your variables (BASIC version):** the app overwrites the real variables A to Z and θ, the strings Str0 to Str9, and the matrix [J]. It also creates lists named CHM, CHEN, CHZ, CHN, CHA to CHE, and CHR. Save anything you need in those first. Choosing **QUIT** from the main menu deletes the lists, [J], and Str0. The native version doesn't touch any of these.
- **Graph settings (BASIC CE shape chart):** the chart draws on the graph screen. It saves your graph settings (window, Y= functions, and format) in GDB9 and puts them back when you leave the chart, then deletes GDB9, so a GDB9 of your own would be replaced. It also turns stat plots off and sets Full screen mode, and those stay that way. The native version leaves all of this alone.

## 8. Troubleshooting

| What you see | What to do |
|---|---|
| `ERR:ARCHIVED` (BASIC) | The programs are in Archive. Press **2nd**, **MEM**, **2: Mem Mgmt**, **Prgm**. Highlight each program marked with `*` and press **ENTER** to move it to RAM. |
| `ERR:MEMORY` (BASIC, usually the TI-84 Plus) | Free RAM by archiving your other programs and lists from the same Mem Mgmt menu. |
| `ERR:UNDEFINED`, or an error right after choosing a chapter (BASIC) | A `ZCHEM...` program is missing. All 18 programs need to be on the calculator; see [Setup](#9-setup-loading-the-app). |
| `ERR:SYNTAX` after typing a number (BASIC) | Usually a negative number typed with the minus key instead of **(-)**. Choose **1: Quit**, start the app again, and use **(-)**. |
| `NOT FOUND` or `not found, try again` at an element prompt | Check the symbol, or enter the atomic number instead. On the native version, Xe, Y, Yb, Zn, and Zr have to be entered by number (see [Elements](#elements)). |
| The native program won't start from the PRGM menu | On OS 5.4 or older run it with `Asm(` (see [Start the app](#start-the-app)). On OS 5.5 and later it has to be started through arTIfiCE or AsmHook2. |
| A message about LibLoad or missing libraries | `clibs.8xg` isn't on the calculator, or isn't in Archive. Send it again. |
| **NOTES LOCKED**, "no valid license found" | One of these: `CHEMLIC.8xv` isn't on the calculator; it was made for a different calculator; or `CHEMNOTE.8xv` is missing or doesn't match the program. Check all three files. If they're right and it still says this, send your ID again. |
| **NOTES LOCKED**, "no device ID" | The program couldn't read this calculator's ID. Contact the person who set up your calculator. |
| **notes error**, "page failed to open" | `CHEMNOTE.8xv` is damaged. Send it again. |
| The app is gone, or won't run, around an exam | Press-to-Test turns off programs, and leaving it may delete files. Load the files again, including the license. |
| Stat plots are off after using the shape chart (BASIC CE) | The chart turns them off. Turn them back on with **2nd**, **STAT PLOT**. Your other graph settings are put back automatically. |
| An answer looks wrong | Check the units the prompt asks for (nm or m, g or kg, J or kJ/mol). Use the **(-)** key for negative numbers, and enter 0 only for the value you want the tool to find. |

## 9. Setup: loading the app

Most calculators come with the app already loaded. If you need to load it yourself, use **TI Connect CE** (free from Texas Instruments) with the calculator connected by USB.

**BASIC version:** send all 18 `.8xp` files from the folder for your calculator (`CE` for the TI-84 Plus CE, `PLUS` for the TI-84 Plus) to **RAM**, not Archive. Then check that `CHEM117` and the `ZCHEM...` programs are in the PRGM list. On a TI-84 Plus, archive your other programs and lists first, since the app needs nearly all of its 24 KB of RAM.

**Native version (TI-84 Plus CE):**

1. Check the OS version with **2nd**, **MEM**, **1: About**. OS 5.4 or older needs nothing extra. OS 5.5 to 5.8.4 needs arTIfiCE v2.1, and OS 5.8.5 or later needs arTIfiCE v3 with TI's Inequalz app and the AsmHook2 app. TI doesn't allow going back to an older OS, so don't update the OS on a calculator that runs the native version without them.
2. Send `clibs.8xg`, `CHEM117N.8xp`, `CHEMNOTE.8xv`, and the calculator's own `CHEMLIC.8xv` to **Archive**.
3. Keep a copy of each calculator's `CHEMLIC.8xv`, since leaving exam mode can delete it. When updating the app, replace `CHEM117N.8xp` and `CHEMNOTE.8xv` together; they come as a pair.
