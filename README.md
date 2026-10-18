# Zadanie 5 — ekran logowania

Zrobiłem prosty ekran logowania w ConstraintLayout.

Na ekranie jest logo, pole e-mail, pole hasła, CheckBox i dwa przyciski.

Logo zrobiłem za pomocą ImageView i DimensionRatio 1:1, żeby miało kwadratowy kształt.

Pole hasła ma inputType textPassword, więc wpisane znaki są ukrywane.

Wszystkie napisy umieściłem w strings.xml.

## Co się psuje w orientacji poziomej?

Po obróceniu telefonu ekran ma mniej miejsca w pionie.

Elementy są ustawione jeden pod drugim, dlatego dolne przyciski mogą nie mieścić się na ekranie.

Problemem jest brak przewijania ekranu.

Żeby to naprawić, można byłoby zastosować ScrollView albo przygotować osobny układ dla orientacji poziomej.
