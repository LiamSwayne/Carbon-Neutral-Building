# Carbon Neutral Building
A linear program that takes a set of parameters and calculates the cheapest combination of materials and carbon-offsets to build a carbon neutral building.

The test cases below are auto-generated by GitHub Actions every time a commit is made.
<!-- TEST CASE 1 -->
```python
Parameters given: 3 floor, 4 tile x length, 10 tile y length.

Cost (measured in USD): $581644.5

columns (measured in quantity):
Wood columns needed: Sum([[-0.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]], None, False)
Steel columns needed: Sum([[591.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]], None, False)

Carbon offsets (measured in acres):
Slash pine acres: 1727.0
```
<!-- END TEST CASE -->

<!-- TEST CASE 2 -->
```python
Parameters given: 5 floor, 2 tile x length, 3 tile y length.

Cost (measured in USD): $603214.9

columns (measured in quantity):
Wood columns needed: Sum([[-0.00 -0.00 -0.00]
 [-0.00 -0.00 -0.00]], None, False)
Steel columns needed: Sum([[985.00 -0.00 -0.00]
 [-0.00 -0.00 -0.00]], None, False)

Carbon offsets (measured in acres):
Slash pine acres: 2877.0
```
<!-- END TEST CASE -->

<!-- TEST CASE 3 -->
```python
Parameters given: 1 floor, 10 tile x length, 10 tile y length.

Cost (measured in USD): $323103.3

columns (measured in quantity):
Wood columns needed: Sum([[-0.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]
 ...
 [-0.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]], None, False)
Steel columns needed: Sum([[197.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]
 ...
 [-0.00 -0.00 ... -0.00 -0.00]
 [-0.00 -0.00 ... -0.00 -0.00]], None, False)

Carbon offsets (measured in acres):
Slash pine acres: 576.0
```
<!-- END TEST CASE -->