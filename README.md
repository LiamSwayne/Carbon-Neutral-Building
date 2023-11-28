# Carbon Neutral Building
A linear program that takes a set of parameters and calculates the cheapest combination of materials and carbon-offsets to build a carbon neutral building.

Exclusions:
- We are excluding the cost of site assessment. We assume that the land can be built on and a concrete foundation already exists, and that all floors are identical.
- We exclude the labor cost. The final estimate is the cost of materials only.

The test cases below are auto-generated by GitHub Actions every time a commit is made.
<!-- TEST CASE 1 -->
```python
Parameters given: 3 floor, 20 meter x length, 25 meter y length.

Cost of materials and offsets (measured in USD): $139309.48

Columns (measured in quantity):
Aluminum columns needed: 0
Steel columns needed: 789

Carbon offsets (measured in acres):
Oak tree acres: 0.32
Slash pine acres: 0.64
Eucalyptus tree acres: 0.64

Number of parking spaces needed: 166
```
<!-- END TEST CASE -->

<!-- TEST CASE 2 -->
```python
Parameters given: 5 floor, 15 meter x length, 40 meter y length.

Cost of materials and offsets (measured in USD): $346766.19

Columns (measured in quantity):
Aluminum columns needed: 0
Steel columns needed: 2625

Carbon offsets (measured in acres):
Oak tree acres: 0.69
Slash pine acres: 1.37
Eucalyptus tree acres: 1.37

Number of parking spaces needed: 333
```
<!-- END TEST CASE -->

<!-- TEST CASE 3 -->
```python
Parameters given: 1 floor, 40 meter x length, 20 meter y length.

Cost of materials and offsets (measured in USD): $56021.65

Columns (measured in quantity):
Aluminum columns needed: 0
Steel columns needed: 140

Carbon offsets (measured in acres):
Oak tree acres: 0.16
Slash pine acres: 0.31
Eucalyptus tree acres: 0.31

Number of parking spaces needed: 88
```
<!-- END TEST CASE -->
