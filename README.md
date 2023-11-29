# Carbon Neutral Building
A linear program that takes a set of parameters and calculates the cheapest combination of materials and carbon-offsets to build a carbon neutral building.

Exclusions:
- We are excluding the cost of site assessment. We assume that the land can be built on and a concrete foundation already exists, and that all floors are identical.
- We exclude the labor cost. The final estimate is the cost of materials only.

The test cases below are auto-generated by GitHub Actions every time a commit is made.
<!-- TEST CASE 1 -->
```python
Parameters given: 3 floor, 20 meter x length, 25 meter y length.

Cost of materials and offsets (measured in USD): $148813.23

Columns (measured in quantity):
Aluminum columns needed: 0
Steel columns needed: 789

Carbon offsets (measured in acres):
Oak tree acres: 0.38
Slash pine acres: 0.76
Eucalyptus tree acres: 0.76

Number of parking spaces needed: 166
```
<!-- END TEST CASE -->

<!-- TEST CASE 2 -->
```python
Parameters given: 5 floor, 15 meter x length, 40 meter y length.

Cost of materials and offsets (measured in USD): $365773.70

Columns (measured in quantity):
Aluminum columns needed: 0
Steel columns needed: 2625

Carbon offsets (measured in acres):
Oak tree acres: 0.81
Slash pine acres: 1.61
Eucalyptus tree acres: 1.61

Number of parking spaces needed: 333
```
<!-- END TEST CASE -->

<!-- TEST CASE 3 -->
```python
Parameters given: 1 floor, 40 meter x length, 20 meter y length.

Cost of materials and offsets (measured in USD): $61090.32

Columns (measured in quantity):
Aluminum columns needed: 0
Steel columns needed: 140

Carbon offsets (measured in acres):
Oak tree acres: 0.19
Slash pine acres: 0.38
Eucalyptus tree acres: 0.38

Number of parking spaces needed: 88
```
<!-- END TEST CASE -->
