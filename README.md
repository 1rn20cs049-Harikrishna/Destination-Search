In this project, let's build a **Destination Search** app by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/destination-search-output-v2.gif" alt="destination search output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/destination-search-sm-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/destination-search-lg-output-v2.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>
 
### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- Initially, all destinations in the `destinationsList` should be displayed
- When a value is provided in the search input, only the destinations whose names contain the value provided in the search input should be displayed irrespective of the case
- The `DestinationSearch` component receives the `destinationsList` as a prop. It consists of a list of destination objects with the following properties in each destination object

  |  Key   | Data Type |
  | :----: | :-------: |
  |   id   |  Number   |
  |  name  |  String   |
  | imgUrl |  String   |

</details>

<details>
<summary>Components Structure</summary>

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/destination-search-component-structure-v2-img.png" alt="destination search component structure" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

</details>

<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/DestinationSearch/index.js`
- `src/components/DestinationSearch/index.css`
- `src/components/DestinationItem/index.js`
- `src/components/DestinationItem/index.css`
</details>


### Resources

<details>
<summary>Image URLs</summary>

- [https://assets.ccbp.in/frontend/react-js/destinations-search-icon-img.png](https://assets.ccbp.in/frontend/react-js/destinations-search-icon-img.png) alt should be **search icon**

</details>

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #252627; width: 150px; padding: 10px; color: white">Hex: #252627</div>
<div style="background-color: #0f172a; width: 150px; padding: 10px; color: white">Hex: #0f172a</div>
<div style="background-color: #f1f5f9; width: 150px; padding: 10px; color: black">Hex: #f1f5f9</div>
<div style="background-color: #000000; width: 150px; padding: 10px; color: white">Hex: #000000</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto
- Open Sans

</details>

