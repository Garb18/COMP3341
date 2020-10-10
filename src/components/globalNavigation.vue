<template>
  <!--Start of Navbar-->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <!--Start of Brand-->
    <a class="navbar-brand" href="index.html">
      <img
        alt
        class="d-inline-block align-center"
        height="30"
        src="../assets/brand/bear.png"
        width="30"
      /> Roundabout Reservations
    </a>
    <!--Start of Navbar responsiveness-->
    <!--Main Navbar content-->
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active">
          <!--Home button-->
          <a class="nav-link" href="#">
            Home
            <span class="sr-only">(current)</span>
          </a>
        </li>
        <li class="nav-item dropdown">
          <!--Dropdown-->
          <a
            aria-expanded="false"
            aria-haspopup="true"
            class="nav-link dropdown-toggle"
            data-toggle="dropdown"
            href="#"
            id="navbarDropdown"
            role="button"
          >Partner with us</a>
          <div aria-labelledby="navbarDropdown" class="dropdown-menu">
            <a class="dropdown-item" href="#">Action</a>
            <!--Dropdown item-->
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="restaurant.php">Restaurants</a>
            <!--Dropdown item-->
          </div>
        </li>
      </ul>
      <!--Start of Search bar-->
      <form class="form-inline my-2 my-lg-0">
        <input aria-label="Search" class="form-control mr-sm-2" placeholder="Search" type="search" />
        <button class="btn btn-outline-light my-2 my-sm-0" type="submit">Search</button>
      </form>
      <!--End of Search Bar-->
    </div>
  </nav>
  <!--End of Navbar-->
</template>

<script>
export default {
  name: "globalNavigation",
  data() {
    return {};
  }
};
</script>
