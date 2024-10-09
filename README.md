
# 🚀👾 Hi there! 👾🚀

I'm Emilio, and I'm a **Computer Science** graduate. <br>
🚀 Recently, I've been studying and working with ***Angular 14*** 🚀

👽 I love working with **Java**, **Python**, **PHP**, and **TypeScript** 👽

## 🛸 Code Samples 🛸

### Code Samples - Java, Python, PHP, and TypeScript

```java
import java.util.Arrays;

public class QuickSortExample {
    public static void quickSort(int[] array, int low, int high) {
        if (low < high) {
            int pi = partition(array, low, high);

            quickSort(array, low, pi - 1);
            quickSort(array, pi + 1, high);
        }
    }

    private static int partition(int[] array, int low, int high) {
        int pivot = array[high];
        int i = (low - 1);
        for (int j = low; j < high; j++) {
            if (array[j] < pivot) {
                i++;

                // swap array[i] and array[j]
                int temp = array[i];
                array[i] = array[j];
                array[j] = temp;
            }
        }

        // swap array[i+1] and array[high] (pivot)
        int temp = array[i + 1];
        array[i + 1] = array[high];
        array[high] = temp;

        return i + 1;
    }

    public static void main(String[] args) {
        int[] data = { 8, 7, 2, 1, 0, 9, 6 };
        System.out.println("Unsorted array: " + Arrays.toString(data));

        quickSort(data, 0, data.length - 1);

        System.out.println("Sorted array: " + Arrays.toString(data));
    }
}
```

```python
print("Hello, World! 👾")
```

```php
<?php
$names = array("Emilio", "Ana", "Carlos", "Lucia");
?>
<!DOCTYPE html>
<html>
<head>
    <title>List of Names</title>
</head>
<body>
    <h1>List of Names 🚀</h1>
    <ul>
        <?php foreach($names as $name): ?>
            <li><?php echo htmlspecialchars($name); ?> 👽</li>
        <?php endforeach; ?>
    </ul>
</body>
</html>
```

```typescript
function sum(a: number, b: number): number {
    return a + b;
}

const result = sum(10, 15);
console.log(`The sum is: ${result}`); // The sum is: 25
```

## 🚀 Contact Me 🚀

Connect with me to collaborate on exciting projects! 👾👽
- [Portfolio](https://alfredoht29.github.io/)
- [LinkedIn](www.linkedin.com/in/emilioaperez)
- [Email](mailto:emilioaperezvilla@outlook.com)

---

Thanks for visiting my profile! 🚀👾👽
