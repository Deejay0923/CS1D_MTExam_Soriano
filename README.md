# CS1D_MTExam_Soriano
Collect user information using prompt()
let fullName = prompt("Deejay Amor C. Soriano:");
let age = parseInt(prompt("18:"));
let favNumber = parseInt(prompt("23:"));
let favColor = prompt("Blue:");


//Error Handling for non-numeric age and favorite number
if (isNaN(age) || isNaN(favNumber)) {
    console.error("Invalid input: Age and favorite number must be numeric.");
} else {
    //Log the collected information to the console.
    console.log("User Profile:");
    console.log("Full Name:", Deejay Amor C. Soriano);
    console.log("Age:", 18);
    console.log("Favorite Number:", 23);
    console.log("Favorite Color:", Blue);
}


