### Refer to the video below:

<br/>
<div style="text-align: center;">
  <video style="max-width:80%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12);outline:none;" loop="true" autoplay="autoplay" controls="controls" muted>
    <source src="https://assets.ccbp.in/frontend/content/react-js/prime-video-output.mp4" type="video/mp4">
  </video>
</div>
<br/>

### Design Files

<details>
<summary>Click to view</summary>

- [Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/prime-video-lg-output-img.png)

</details>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- **Action Movies List** and **Comedy Movies List** should be displayed using **React Slick**
- The `App` is provided with `moviesList`. It consists of a list of movieItem objects with the following properties in each movieItem object

  |     Key      | Data Type |
  | :----------: | :-------: |
  |      id      |  String   |
  | thumbnailUrl |  String   |
  |   videoUrl   |  String   |
  |  categoryId  |  String   |

- When the **next button** is clicked in any of the sliders, the next movie items thumbnail in the corresponding moviesList should be displayed
- When the **previous button** is clicked in any of the sliders, the previous movie items thumbnail in the corresponding moviesList should be displayed <br/>

  <div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/prime-video-next-previous-buttons-img.png" alt="movie slider buttons" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
  </div>
<br/>

- When you click on the **thumbnail**, then the popup should be opened,

  - And corresponding video should be displayed using **React player** component from `react-player`
    <div style="text-align: center;">
      <img src="https://assets.ccbp.in/frontend/content/react-js/prime-video-popup-img.png" alt="popup" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
  </div>
  <br/>
  - When the close button is clicked, then the popup should be closed

</details>

<details>
<summary>Components Structure</summary>

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/prime-video-compoment-structure-breakdown.png" alt="component structure breakdown" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

</details>

<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/PrimeVideo/index.js`
- `src/components/PrimeVideo/index.css`
- `src/components/MoviesSlider/index.js`
- `src/components/MovieItem/index.js`
- `src/components/MovieItem/index.css`

</details>
