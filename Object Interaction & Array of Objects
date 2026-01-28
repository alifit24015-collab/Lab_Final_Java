class Book {
    int bookId;
    String title;
    double price;

    Book(int bookId, String title, double price) {
        this.bookId = bookId;
        this.title = title;
        this.price = price;
    }

    void display() {
        System.out.println("ID: " + bookId +
                           ", Title: " + title +
                           ", Price: " + price);
    }
}

public class BookTest {
    public static void main(String[] args) {

        Book[] books = new Book[5];

        books[0] = new Book(101, "Java Basics", 450);
        books[1] = new Book(102, "OOP in Java", 650);
        books[2] = new Book(103, "Data Structures", 800);
        books[3] = new Book(104, "Algorithms", 550);
        books[4] = new Book(105, "Database Systems", 400);

        double sum = 0;

        System.out.println("Books with price greater than 500:");
        for (Book b : books) {
            if (b.price > 500) {
                b.display();
            }
            sum += b.price;
        }

        double averagePrice = sum / books.length;
        System.out.println("\nAverage Price of all books: " + averagePrice);
    }
}
