# Postman Collection to Marvel API
Postman Collection to Test few Marvel API end points.

* Go to [Marvel Developer Page](https://developer.marvel.com/) to Sign in and get
   * Public Key
   * Private Key
* Import the *Testing Marvel API.postman_collection.json* to your Postman Environment
* When Editing your Collection, go to the *Pre-request* Tab
* Edit *pubkey* and *pvtkey* variables values to the one you've just get at **Marvel Developer Page**
* Other **Enviromnent Variables** will be automatically created, they are:
    * **ts**: Time stamp required
    * **apikey**: The same *pubkey* value
    * **hash**: Hash in MD5 created from *ts*, *pubkey* and *pvtkey*
> Time to Run! Good Luck! /play greatjob

This file was written with [Dillinger.io](https://dillinger.io/) Online Editor and :octocat:

 


