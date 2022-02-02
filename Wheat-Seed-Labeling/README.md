# Overviwe

In this project I tried to use differant sklearn packages to predict label of wheat.

# Features

1. area A,
2. perimeter P,
3. compactness C = 4*pi*A/P^2,
4. length of kernel,
5. width of kernel,
6. asymmetry coefficient
7. length of kernel groove.
8. 
All of these parameters were real-valued continuous.


# Walkthrough

I imported my libraries and model, then I faces some conflicts and problems with dataset and I solved them. Then I tried to get some information
and drop unwanted columns (*some of them were duplicated according their correlation*). Finally I appiled my models and evaluated them and I tried to
tune them a little bit to see whether I can get better results or not.

**there is one warning in the note book that is because of the penalty**

# Results

<table>
  <tr>
    <th>      </th>
    <th>knn</th>
    <th>lr</th>
    <th>dtc</th>
    <th>rfc</th>
    <th>svc</th>
    <th>sgd</th>
  </tr>
  <tr>
    <td>Raw Accuracy</td>
    <td>87</td>
    <td>85</td>
    <td>89.6</td>
    <td>87</td>
    <td>87</td>
    <td>87</td>
  </tr>
  <tr>
    <td>tuned Accuracy</td>
    <td>91.4</td>
    <td>88.5</td>
    <td>88</td>
    <td>90</td>
    <td>91.4</td>
    <td>89</td>
  </tr>
</table> 
