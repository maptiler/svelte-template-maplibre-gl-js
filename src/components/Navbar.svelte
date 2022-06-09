<div class="heading">
  <a href="https://documentation.maptiler.com/hc/en-us/articles/4416984762641-how-to-display-a-map-in-svelte-using-maplibre-gl-js?utm_medium=referral&utm_source=github&utm_campaign=2022-05%20%7C%20js%20frameworks%20%7C%20svelte" class="btn btn-primary tutorial-button">
    <svg width="25" height="25" viewBox="0 0 111 111" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M13.1618 75.4536C2.1417 64.4335 2.14171 46.5664 13.1618 35.5463L35.9431 12.7651C46.9632 1.74497 64.8303 1.74498 75.8504 12.7651L98.6317 35.5464C109.652 46.5665 109.652 64.4335 98.6316 75.4536L75.8503 98.2349C64.8303 109.255 46.9632 109.255 35.9431 98.2349L13.1618 75.4536Z" fill="#3174ff" stroke="#fff" stroke-width="8"/>
      <path d="M59.3986 52.5H29.3987V58.4999H59.3986V52.5ZM65.3986 40.5H29.3987V46.5H65.3986V40.5ZM29.3987 70.4999H53.3986V64.4999H29.3987V70.4999Z" fill="#fff"/>
      <path d="M59.3911 64.875V70.5H65.0161L81.606 53.9101L75.9811 48.2851L59.3911 64.875ZM85.956 49.5601C86.541 48.9751 86.541 48.0301 85.956 47.4451L82.446 43.9351C81.861 43.3501 80.916 43.3501 80.3311 43.9351L77.5861 46.6801L83.211 52.3051L85.956 49.5601Z" fill="#fff"/>
    </svg>
    Step-by-step tutorial
  </a>

  <h1>This is my map App</h1>

  <a href="https://github.com/maptiler/svelte-template-maplibre-gl-js" class="github-corner" aria-label="View source on GitHub">
    <svg width="50" height="50" viewBox="0 0 50 50" fill="none" style="position: absolute; top: 14px; border: 0; right: 17px;" xmlns="http://www.w3.org/2000/svg">
      <path d="M25 0C11.1937 0 0 11.1938 0 25C0 36.7146 8.06667 46.5167 18.9417 49.2292C18.825 48.8917 18.75 48.5 18.75 48.0146V43.7417C17.7354 43.7417 16.0354 43.7417 15.6083 43.7417C13.8979 43.7417 12.3771 43.0063 11.6396 41.6396C10.8208 40.1208 10.6792 37.7979 8.65 36.3771C8.04792 35.9042 8.50625 35.3646 9.2 35.4375C10.4812 35.8 11.5437 36.6792 12.5437 37.9833C13.5396 39.2896 14.0083 39.5854 15.8687 39.5854C16.7708 39.5854 18.1208 39.5333 19.3917 39.3333C20.075 37.5979 21.2562 36 22.7 35.2458C14.375 34.3896 10.4021 30.2479 10.4021 24.625C10.4021 22.2042 11.4333 19.8625 13.1854 17.8896C12.6104 15.9313 11.8875 11.9375 13.4062 10.4167C17.1521 10.4167 19.4167 12.8458 19.9604 13.5021C21.8271 12.8625 23.8771 12.5 26.0312 12.5C28.1896 12.5 30.2479 12.8625 32.1187 13.5063C32.6562 12.8542 34.9229 10.4167 38.6771 10.4167C40.2021 11.9396 39.4708 15.95 38.8896 17.9042C40.6312 19.8729 41.6562 22.2083 41.6562 24.625C41.6562 30.2438 37.6896 34.3833 29.3771 35.2438C31.6646 36.4375 33.3333 39.7917 33.3333 42.3188V48.0146C33.3333 48.2313 33.2854 48.3875 33.2604 48.5729C43.0021 45.1583 50 35.9083 50 25C50 11.1938 38.8062 0 25 0Z" fill="white"/>
    </svg>
  </a>
</div>

<style>
  .heading {
    margin: 0;
    padding: 0px;
    background-color: black;
    color: white;
  }

  .heading > h1 {
    padding: 20px;
    margin: 0;
  }

  .btn {
    display: inline-block;
    font-family: ubuntu,open sans,sans-serif;
    font-weight: 500;
    line-height: 15px;
    color: #6b7c92;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    cursor: pointer;
    user-select: none;
    background-color: transparent;
    border: 0 solid transparent;
    padding: 10px 17px;
    font-size: .8125rem;
    border-radius: 4px;
    transition: color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out,box-shadow .15s ease-in-out;
    text-transform: uppercase;
  }

  .btn-primary {
    color: #fff;
    background-color: #3174ff;
    border-color: #3174ff;
  }

  .tutorial-button {
    left: 20px;
    position: absolute;
    top: 16px;
    border-radius: 4px;
    text-decoration: none;
    vertical-align: middle;
  }

  .tutorial-button svg {
    vertical-align: middle;
    margin-right: 10px;
  }

</style>