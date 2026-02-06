
import java.io.FileOutputStream;
import java.io.IOException;

public class ByteWriteDemo {

    public static void main(String[] args) {

        // Try-with-resources ensures the stream is closed automatically
        try (FileOutputStream fos = new FileOutputStream("data.bin")) {

            fos.write(65);   // Writes ASCII value of 'A'
            System.out.println("Data written using byte stream");

        } catch (IOException e) {
            System.out.println("File writing error: " + e.getMessage());
        }
    }
}
