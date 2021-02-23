import java.util.Calendar;

public class AddDates {

    public static void main(String[] args) {

        Calendar c1 = Calendar.getInstance();
        Calendar c2 = Calendar.getInstance();
        Calendar cTotal = (Calendar) c1.clone();

        cTotal.add(Calendar.YEAR, c2.get(Calendar.YEAR));
        cTotal.add(Calendar.MONTH, c2.get(Calendar.MONTH) + 1); // Zero-based months
        cTotal.add(Calendar.DATE, c2.get(Calendar.DATE));
        cTotal.add(Calendar.HOUR_OF_DAY, c2.get(Calendar.HOUR_OF_DAY));
        cTotal.add(Calendar.MINUTE, c2.get(Calendar.MINUTE));
        cTotal.add(Calendar.SECOND, c2.get(Calendar.SECOND));
        cTotal.add(Calendar.MILLISECOND, c2.get(Calendar.MILLISECOND));

        System.out.format("%s + %s = %s", c1.getTime(), c2.getTime(), cTotal.getTime());

    }
}
https://episodefilm.com/%d8%b3%d8%a7%d8%ae%d8%aa-%d8%aa%db%8c%d8%b2%d8%b1-%d8%aa%d8%a8%d9%84%db%8c%d8%ba%d8%a7%d8%aa%db%8c/
