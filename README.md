# Responsivecart
#this is my first webpage using bootstarp


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>


    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">

        <script src="https://kit.fontawesome.com/c74b69ca0a.js" crossorigin="anonymous"></script>

</head>

<body>

    <div class="bg-light">
        <div class="container">
            <div class="textcenter py-5 ">
                <img src="A-logo.svg"
                 class="d-block mx-auto mb-4" height="70" width="70" alt="">

                <h2 class="text-center mb-3">Check-Out</h2>

                <p class="lead ">This is Adnan's First project using Bootstrap ,HTML,CSS and this is a check out form
                    like we have in amazon,flipkart and many more when we buy some things online and during checkout of
                    all our products same page is shown and hoping to create many projects like this to improve my
                    skills.</p>
            </div>

            <div class="row">
                <div class="col-md-3 order-col-2 ">
                    <h4 class="text-muted mb-3">Your-Cart</h4>

                    <ul class="list-group mb-3">

                        <li class="justify-content-between  list-group-item d-flex">
                            <div>
                                <h6>First-Item </h6>
                                <small class="text-muted">Description</small>
                            </div>
                            <span>$15</span>
                        </li>

                        <li class="justify-content-between list-group-item  d-flex">
                            <div>
                                <h6>Second Item</h6>
                                <small class="text-muted">Description</small>
                            </div>
                            <span>$8</span>
                        </li>
                        <li class="justify-content-between d-flex list-group-item">
                            <div>
                                <h6>Third-Item</h6>
                                <small class="text-muted">Description</small>
                            </div>
                            <span>$30</span>
                        </li>

                        <li class="justify-content-between d-flex list-group-item bg-light">
                            <div class="text-success">
                                <h6>PROMO-CODE</h6>
                                <small class="text-success">APPLIED</small>
                            </div>
                            <span class="text-success">-$5</span>
                        </li>
                        <li class="justify-content-between d-flex list-group-item">
                            <div>
                                <h5>TOTAL(USD)</h5>
                            </div>
                            <span>$43</span>
                        </li>
                    </ul>

                    <form class="mb-3 card p-3">
                        <div class="input-group">
                            <input type="text" placeholder="Search Promocode">

                            <div class="input-group-append">
                                <button type="submit" class="btn btn-secondary">REEDEM </button>
                            </div>
                        </div>
                    </form>

                </div>
                <div class="col-md-8 order-md-1 mx-auto">
                    <h4 class="mb-3">Billing address</h4>
                    <form action="">
                        <div class="row">
                            <div class="mb-3 col-md-6">
                                <label for="first-name " class="form-label">First Name</label>
                                <input type="text" id="first-name" class="form-control">
                            </div>
                            <div class="mb-3 col-md-6">
                                <label for="last-name" class="form-label">Last Name</label>
                                <input type="text" id="last-name" class="form-control">
                            </div>
                        </div>
                        <div class="mb-3 ">
                            <label for="username">Username</label>
                            <div class="input-group mb-3">
                                <div class="input-group-prepend">
                                    <span class="input-group-text">@</span>
                                </div>
                                <input type="text" placeholder="Username" class="form-control" id="username">

                            </div>

                            <label for="Email">
                                Email
                                <small class="text-muted">(Optional)</small>
                            </label>
                            <input type="text" class="form-control mb-3" id="Email" placeholder="you@gmail.com">


                            <label for="address" class="form-label">Address</label>
                            <input type="text" placeholder="22-1-693,BSWD,Telangana" class="form-control mb-3">

                            <div class="row">
                                <div class="col-md-5 mb-3">
                                <label for="country" class="mb-2 form-label" >Country</label>
                                <select name=""  class="custom-select d-block w-100"   id="country">
                                    <option value>choose...</option>
                                    <option value="India">India</option>
                                    <option value="Bangladesh">Bangladesh</option>
                                    <option value="Australia">Australia</option>
                                    <option value="us">United States</option>
                                    <option value="uk">U.K</option>
                                </select>

                                </div>

                                <div class="col-md-4 mb-3">
                                    <label for="state" class="mb-2 form-label">State</label>

                                    <select name="" id="state" class="custom-select d-block w-100">
                                        <option value="">Telangana</option>
                                        <option value="">Andhra</option>
                                        <option value="">Kerala</option>
                                        <option value="">Tamilnadu</option>
                                    </select>
                                </div>
                                <div class="col-md-3 mb-3">
                                    <label for="zip" class="mb-2 form-label">ZIP</label>
                                    <input type="number" name="" id="zip" class="form-select">                                
                                
                                </div>


                            </div>

                            

                            <hr class="mb-4">

                            <div class="checkbox">
                                <div class="checkbox1 mb-1">
                                <input type="checkbox" class="form-check-input me-2" name="" id="checkbox">
                                <label for="checkbox" class="form-check-label ">Shipping address is the same as my billing address</label>
                                </div>
                                <div class="checkbox2 mb-1">
                                <input type="checkbox" class="form-check-input me-2" name="" id="checkbox">
                                <label for="checkbox" class="form-check-label ">Save this information for next time</label>

                                </div>                          
                            
                            </div>

                            <hr class="mb-4">

                            <div class="payment mb-4">

                                <h3 class="mb-3">Payment</h3>

                                <div class="custom-control custom-radio">
                                    <input type="radio" class="custom-control-input me-2" name="payment-method" id="debit">
                                    <label for="radio" class="custom-control-label">UPI</label>
                                    
                                </div>
                                <div class="custom-control custom-radio">
                                    <input type="radio" class="custom-control-input me-2" name="payment-method" id="debit">
                                    <label for="radio" class="custom-control-label">Credit-card</label>
                                    
                                </div>
                                <div class="custom-control custom-radio">
                                    <input type="radio" class="custom-control-input me-2" name="payment-method" id="debit">
                                    <label for="radio" class="custom-control-label">Debit-card</label>
                                    
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-md-6 mb-3">
                                    <label for="name" class="form-label">Name on card</label>
                                    <input type="text" name="" id="name" class="form-control">
                                    <small class="text-muted">Full name as displayed on card</small>
                                </div>
                                <div class="col-md-6 mb-3">
                                    <label for="card-number" class="form-label">Credit Card Number</label>
                                    <input type="number" name="" id="card-number" class="form-control">

                                </div>

                                <div class="col-md-3 mb-3">
                                    <label for="expiration" class="form-label">Expiration</label>
                                    <input type="number" name="" id="expiration" class="form-control">
                                </div>
                                <div class="col-md-3 mb-3">
                                    <label for="cvv" class="form-label">CVV</label>
                                    <input type="number" name="" id="cvv" class="form-control">
                                </div>
                            </div>
                            <hr class="mb-4">

                            <button type="button" class="col-md-12 btn btn-primary btn-lg">Continue to checkout</button>




                        </div>
                    </form>
                </div>
            </div>

        </div>

        <footer class="my-5 text-center text-muted">
            <p class="mb-1">&copy; 2022-2023 &nbsp; Adnan's Company</p>

            <ul class="list-inline">
                <li class="list-inline-item"><a href="#" >Privacy</a></li>
                <li class="list-inline-item"><a href="#">Terms</a></li>
                <li class="list-inline-item"><a href="#">Support</a></li>
            </ul>
        </footer>
    </div>






    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm"
        crossorigin="anonymous"></script>
</body>

</html>
