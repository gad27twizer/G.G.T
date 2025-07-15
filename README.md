# G.G.T
import java.time.LocalTime;
import java.time.format.DateTimeFormatter;

public class ShowCurrentTimeOnce {
    public static void main(String[] args) {
        LocalTime currentTime = LocalTime.now();
        DateTimeFormatter formatter = DateTimeFormatter.ofPattern("HH:mm:ss");
        String timeString = currentTime.format(formatter);

        System.out.println("השעה הנוכחית היא: " + timeString);
    }
}
