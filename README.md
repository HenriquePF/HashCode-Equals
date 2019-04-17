## HashCode and Equals

## Main Topics:
- HashCode and Equals are Object operations used to compare if an object is equal to another;
  - Equals: slow but the answer is 100% true;
  - HashCode: fast but the answer might not be always true;
  
- String, Date, Integer, Double, etc... already have the implementations for those operations. Custom classes must override them.

## Equals:
- Method that compares if an object is equal to another, returning true or false;

## HashCode:
- Method that returns an integer that represents a generated code from the informations of an object;
  - If the HashCode of two objects are different, then the two objects are different;
  - If the code from the two objects are equal, it is highly possible that the objects are equal(might have collision);
  
## How Hash test equality?
- If HashCode and Equals are implemented:
  - First hashcode. If they are equal, use equals to confirm;
  - Remember: String, Integer, Double, etc... already have equals and hashcode;
  
- If hashCode and equals are NOT implemented:
  - Compare the object references;
  
  **-----------------------------------------------------------------------------------**
  
  
  **Remember that i'm in learning process, i'm open for constructive criticism and tips, please, feel free to help, Thanks!**
