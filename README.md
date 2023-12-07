# **Scratch Game Steps**

<hr>

## Layout

## **Step 1**

- Open a blank scratch

## **Step 2**

- Chose a sprite for the catcher, and one for the dropping object. In total should have 2. 
    - Note: Background is optional but you can choose whatever you think fits.
<img src="image12.png" alt="example_image">
<img src="image14.png" alt="example_image">
<img src="image1.png" alt="example_image">

## Code

## **Step 3**

- Go to the code console.
<img src="image13.png" alt="example_image">

- On the sprite you chose for the catcher, add a Flag event and a forever loop. Like shown below.
 <img src="image2.png" alt="example_image">

 ## **Step 4**

 - Inside the forever loop, add 2 if-then statements.
 <img src="image3.png" alt="example_image">

## **Step 5**

- In the empty space, add a key press sensor for the respective arrow keys. Then inside the statements add a **change x by __** action. the left should move negative, the right should move positive
    - note: the larger the number, the faster it'll move. The smaller, the slower.

<img src="image4.png" alt="example_image">

## **Step 6**

- Go to *variables* and create a variable **FOR ALL SPRITES**
<img src="image5.png" alt="example_image">

## **Step 7**

- In the sprite you chose for the falling object, add a flag event. Set the score variable to 0 and add a forever loop.

<img src="image6.png" alt="example_image">

## **Step 8**

- Inside the forever loop, add a **change y by __** action and choose the speed ***should be negative***, the lower the number, the faster the speed. After that, add 2 if block, inside the forever loop as well.
<img src="image7.png" alt="example_image">

## **Step 9**

- In the empty space, add a **touching __** sensor, and set it to the catcher sprite. Then inside the statement change the score counter by 1.

<img src="image8.png" alt="example_image">

## **Step 10**

- Under the change score, add a **go to random position** action, and a **set y to __** action.
    - Note: works better if the value is higher than 180.

<img src="image9.png" alt="example_image">

## **Step 11**

- In the second if block, make a **<** operator for the **y position** to be less than -180/-190. Place that in the empty space.
<img src="image10.png" alt="example_image">

## **Step 12**

- Inside the statement add the same logic as **Step 10**

<img src="image11.png" alt="example_image">

## **Extra**

## **Rotating**

### **Step 1**

- In the sprite you chose for the falling object, add a flag event and a forever loop

<img src="image15.png">

### **Step 2**

- Inside the loop, put a rotate to either left or right action and add a value to whatever you'd like (the larger, the faster it'll rotate.)

<img src="image16.png">