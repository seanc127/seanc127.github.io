# Hello World

This is my home page! My name is Sean Chadbourne and I am a student at [Cal State Fullerton](http://www.fullerton.edu/) and my major is Computer Science.

## Computer Science Projects

My GitHub page is https://github.com/seanc127.

### CPSC 120

* Lab 2

    Lab 2, part 2 was one of my favorite labs as I found the madlib part very easy to understand and useful for the future. It taught me the basics of inputs and outputs and was the introduction of the string type variable for me. I think the learning objective of this lab was to really serve as the beginning for us to begin writing more complex code after Lab 1 and introduce to us the basic string variable while developing the usage of inputs and outputs introduced from Lab 1.

* Lab 3

    Lab 3, part 2 was a lab I thought that was very thought provoking by how it introduced us incorporating formulas into our code. This was something I thought was interesting, as we had finally made something which could calculate a date after you provided it information. I believe the learning objective of this lab was to help us further develop by learning the incorporation of formulas into our projects and storing multiple values in variables for calculating.

    Fliegel & Van Flandern's Algorithm which was implemented in this lab.
    ```
    int month = 1;
    int day = 23;
    int year = 2021;
    int julian_day = day - 32075 + 1461
      * (year + 4800 + (month - 14) / 12) / 4
      + 367 * (month - 2 - (month - 14) / 12 * 12) / 12 - 3
      * ((year + 4900 + (month - 14) / 12) / 100) / 4;
    ```

* Lab 4

    Lab 4, part 2 was something I thought was fun as it was the first semi-interactive program we did. How it worked was the second person would guess the first person's number and with if values you would be told if the number you put was too high or too low. In this lab many new concepts were used such as the comparison operators and else if statements. Overall I think the learning objective was to develop our use of conditional statements while also showing us the use of how we can incorporate messages into our code. Instead of writing the standard error message for the wrong value, we wrote hints for this lab due to it being a game essentially. 

    Example of a hint which would be given.
    ```
    if (first_guess > secret_number) {
    std::cout << "Too high\n";
    ```