<template>

    <header class="shadow p-1 mb-5 bg-light">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <a class="navbar-brand " href="#">YouMeubles</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav mx-auto">
                        <li class="nav-item ml-3 mr-3">
                            <a class="nav-link" href="#">Home</a>
                        </li>
                        <li class="nav-item ml-3 mr-3">
                            <a class="nav-link" href="#">About</a>
                        </li>
                        <li class="nav-item ml-3 mr-3">
                            <a class="nav-link" href="#">Contact</a>
                        </li>
                        <li class="nav-item ml-3 mr-3">
                            <a class="nav-link" href="#">Team</a>
                        </li>
                    </ul>
                    <ul class="navbar-nav">
                        <li class="nav-item">
                           

                            <div class="container">
                                <a class="nav-link" href="#" data-toggle="modal" data-target="#myModal">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                                        <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                                    </svg>
                                </a>
                                <!-- Modal -->
                                    <div class="modal fade" id="myModal" role="dialog">
                                    <div class="modal-dialog modal-lg">
                                        <div class="modal-content">
                                      
                                        <div class="modal-body">
                                            <div class="form-outline">
                                                <input type="text" id="typeText" class="form-control" />
                                            </div>
                                        </div>
                                        <div class="modal-footer">
                                            <button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
                                        </div>
                                        </div>
                                    </div>
                                    </div>
                            </div>
                        </li>
                        <li class="nav-item ml-3">
                            <a class="nav-link text-black" href="#">Sign Up</a>
                        </li>
                        <li class="nav-item ml-3">
                            <a class="nav-link bg-dark text-white  rounded" href="#">Login</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>



</template>

<script>
export default {
  name: 'AppHero',
};
</script>

<style scoped lang="css">

</style>
