# Business Rules
Each pet profile must include the following information:

* Unique pet ID
* Pet's name
* Species (e.g. "Dog", "Cat")
* Breed (e.g., depending on the species, "Labrador Retriever" for dog, "Persian" for cat, etc.)
* Birth date
* Adoption Date (only if already adopted)
* Gender ("Male" or "Female")
* Description
* Image (URL format, assumes that the image was previously saved in an external service)
* Adoption status (e.g. "Available", "Pending", or "Adopted")
* Adoption applications must contain the following information:

* Applicant name
* Applicant email
* Applicant phone number
* Pet you want to adopt
* Notes where you can explain reasons why the adoption request was accepted or rejected (filled out by administrative users)
* Adoption application status (e.g. "Received", "In Review", "Accepted", "Rejected")

## Additional rules to consider
* See list of pets available for adoption
* Allow filters by species, breed, gender, age/lifeStage (puppy < 1 year, adult 1 to 7 years, senior > 7 years)
## Check pet details
* Create an adoption request for specific pets
* Only allow 1 active adoption request per pet
## Adoption Process
* When a user submits an adoption request, update the pet's adoption status to "Pending" so that it will not be displayed until the situation is resolved.

