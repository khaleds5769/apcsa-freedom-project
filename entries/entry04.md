# Entry 4
##### 3/19/23


## Content:
I have been playing around with creating different pages from my swift app. I have experienced challenges throughout the way but I have figured out different solutions to my problem. Any obstacles I have faced, I find solutions using youtube or google. One problem that I was able to overcome was creating a second page for my app. At first, I thought that the only way I could create a second page was by writing code for it, however, I realized that swiftUI can allow me to edit or add different functionalities with the object library. The object library contains different UI elements. I have found this [youtube](https://youtu.be/NGjkEh2FyVE) tutorial helpful in explaining how to go from one view page to another.

```Java 
import UIKit

class second: UIViewController {

    @IBOutlet weak var output: UILabel!
    
    @IBOutlet weak var input: UITextField!
    
    @IBAction func btnClick(_ sender: Any) {
        output.text = input.text
    }
    override func viewDidLoad() {
        super.viewDidLoad()

        // Do any additional setup after loading the view.
    }
    

}

```

One thing I realized after the inheritance unit was that inheritance was involved in swift. For creating two pages, I need to have a class that will be the parent class in which I can create a child class that will inherit all of its methods. For the code above, I created a second page that will inherit the method `.viewDidLoad()` from the parent class. 


Below is the first page of my app: 

<img width="294" alt="Screenshot 2023-03-19 at 10 30 19 PM" src="https://user-images.githubusercontent.com/73479632/226233042-c9dfbb3c-d5a7-4ac7-a5c7-ab8335186693.png">


## Engineering Design Process: 

Currently where I am at in the [Engineering Design Process](https://hstatsep.github.io/students/#edp) is that I am still creating and testing the prototype. I am creating my app and along the way, I am testing it to see what needs to be fixed or what needs to be added in order for it to be an MVP. 



## Skills:

The [skills](https://hstatsep.github.io/students/#skills)that I have gained throughout the learning process of my tool is that I am learning to debug and embrace failure. I encountered many code errors when a specific code I wrote wouldn't work. I would try to find the error within my code by observing closely each line of code. I have also learned to embrace failures because at first, I would feel unmotivated if a piece of code wouldn't work. Now, I am trying to understand why that code didn't work. I value failure because that is what will help me learn and push through my project. 



[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)


