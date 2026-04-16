# android-lab-2

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <com.google.android.material.textfield.TextInputEditText
        android:id="@+id/editTextNumber5"
        android:layout_width="129dp"
        android:layout_height="45dp"
        android:layout_marginTop="204dp"
        android:hint="Druga liczba"
        android:inputType="number"
        android:textSize="15dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toEndOf="@+id/textInputEditText2"
        app:layout_constraintTop_toTopOf="parent" />

    <com.google.android.material.textfield.TextInputEditText
        android:id="@+id/textInputEditText2"
        android:layout_width="129dp"
        android:layout_height="45dp"
        android:layout_marginStart="24dp"
        android:layout_marginTop="204dp"
        android:hint="Pierwsza liczba"
        android:inputType="number"
        android:textSize="15dp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Liczba kliknięć przycisku:"
        android:textColor="@color/blue"
        app:layout_constraintEnd_toStartOf="@+id/editTextNumberSigned2"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/button_1" />

    <com.google.android.material.textfield.TextInputEditText
        android:id="@+id/textInputEditText"
        android:layout_width="227dp"
        android:layout_height="43dp"
        android:layout_marginTop="5dp"
        android:hint="Podaj imię"
        android:textSize="15sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button_1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="5dp"
        android:backgroundTint="@color/cyan"
        android:text="Prześlij imię"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textInputEditText" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="TextView"
        tools:layout_editor_absoluteX="443dp"
        tools:layout_editor_absoluteY="166dp" />

    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="5dp"
        android:text="Dodaj 1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView" />

    <EditText
        android:id="@+id/editTextNumberSigned2"
        android:layout_width="21dp"
        android:layout_height="16dp"
        android:layout_marginEnd="76dp"
        android:ems="10"
        android:inputType="numberSigned"
        app:layout_constraintEnd_toEndOf="parent"
        tools:layout_editor_absoluteY="104dp" />

    <Button
        android:id="@+id/multipli"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="36dp"
        android:layout_marginTop="16dp"
        android:text="Mnożenie"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textInputEditText2"
        app:layout_constraintVertical_bias="0.003" />

    <EditText
        android:id="@+id/editTextText"
        android:layout_width="95dp"
        android:layout_height="45dp"
        android:ems="10"
        android:inputType="text"
        android:text="wynik"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.521"
        app:layout_constraintStart_toEndOf="@+id/multipli"
        app:layout_constraintTop_toBottomOf="@+id/editTextNumber5"
        app:layout_constraintVertical_bias="0.057" />

    <TextView
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="224dp"
        android:text="Różne guziki :)"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toStartOf="parent" />

    <RadioGroup

        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="168dp"
        android:orientation="horizontal"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.5"
        app:layout_constraintStart_toStartOf="parent">

        <RadioButton
            android:id="@+id/radioButton"
            android:layout_width="wrap_content"
            android:layout_height="39dp"
            android:text="kolos" />

        <RadioButton
            android:id="@+id/radioButton2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="egzamin" />

        <RadioButton
            android:id="@+id/radioButton3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="przepis" />

    </RadioGroup>

</androidx.constraintlayout.widget.ConstraintLayout>
