# Exp-09-Write-a-program-to-add-retrieve-and-remove-the-element-from-the-ArrayList.
```
import java.util.ArrayList;

public class ArrayListExample {

    public static void main(String[] args) {
        ArrayList<String> arrayList = new ArrayList<>();
        arrayList.add("akash 1");
        arrayList.add("dhinesh 2");
        arrayList.add("dhaya 3");
        System.out.println("Initial ArrayList: " + arrayList);
        int indexToRetrieve = 1;
        if (indexToRetrieve >= 0 && indexToRetrieve < arrayList.size()) {
            String retrievedElement = arrayList.get(indexToRetrieve);
            System.out.println("Element at index " + indexToRetrieve + ": " + retrievedElement);
        } else {
            System.out.println("Invalid index for retrieval.");
        }
        int indexToRemove = 0;
        if (indexToRemove >= 0 && indexToRemove < arrayList.size()) {
            String removedElement = arrayList.remove(indexToRemove);
            System.out.println("Removed element at index " + indexToRemove + ": " + removedElement);
        } else {
            System.out.println("Invalid index for removal.");
        }
        System.out.println("ArrayList after removal: " + arrayList);
        String newElement = "New siva";
        arrayList.add(newElement);
        System.out.println("ArrayList after addition: " + arrayList);

    }
}

```
#Output
![Screenshot (72)](https://github.com/21002624/Exp-09-Write-a-program-to-add-retrieve-and-remove-the-element-from-the-ArrayList./assets/113762183/3c5fb764-d4ff-463d-a8ae-10e96826b0e0)
