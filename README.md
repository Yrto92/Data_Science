# Data_Science
Projects for a data science course
**Molecular Structure Calculator**
Presented by Ya'eer Kidron & Yair Toledano

Introduction:

The Lewis Theory used observations from chemists and physicists to form a theory about chemical bonding. This work was essentially a compilation of the knowledge at the time. It revolved around the importance of valence electrons in chemical bonding. Valence electrons are the electrons that are in the outermost shell. For example, Na (Sodium) has 11 electrons, but only one is a valence electron, the one in its outermost orbital: 3s1. Meanwhile, P (Phosphorus) has 15 electrons, but has five valence electrons, 3s2 and 3p2. The bonding of an element is based on how they fill their "Octets" - achieve a noble gas electron configuration.
Lewis Theory went on to explain how certain elements such as Boron did not necessarily follow these same rules. He explicitly defined two ways electrons were used to form bonds. These were ionic (complete transfer of electron) and covalent (sharing of electrons) bonding. He added to his covalent bonding theory that atoms can have double or triple bonds with other atoms when electrons are shared. A single bond consists of two electrons sharing between two atoms, double bond consists of four electrons sharing between two atoms, and triple bond consists of six electrons sharing between two atoms. In both cases Lewis dot structures were used to visualize the bonding of the atoms in case of electron sharing or electron transfer.

Goal:
Calculate and visually display the Lewis Model of a given formulae, based on the electron's configuration of all the elements in the periodic-table by the Madelung rule.
The algorithm takes into consideration all the possible oxidation states of each atom, and the ionic/covalent bonds between the atoms. Note - Lewis structure does NOT attempt to explain the geometry of molecules, how the bonds form, or how the electrons are shared between the atoms.
It is the simplest and most limited theory on electronic structure.

Algorithm steps:
- Building a dictionary where for every element there are the available bonds

- Use a predefined periodic table dictionary and formulae, split the chemical formulae string into the different elements, including dealing with parenthesis

- Recursive function that builds the molecule, runs through elements to bond the different atoms based on Madelung rule.

     First Class – Atom: Represents a molecule atom with it's bonds
     Second Class – ChemistryFormulae: Represent a chemistry formula if the initialization succeeds

- The algorithm uses a Brute force approach for searching the correct bonds between the atoms

- Drawing the bonding between atoms of a molecule


![image](https://user-images.githubusercontent.com/98529796/151413483-bc2a1d9d-2737-4881-a4e5-cd1468693e5a.png)

