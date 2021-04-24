# Twoja Lista Zadań
> Twój osobisty dziennik do wpisywania celow na każdy dzień !

## Spis treści
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
Projekt wykonany na zaliczenie przedmiotu w ramach zajęć z Androida. Możliwość zakładania konta i logowania się za pomocą niego dzięki Firebase Authentication. Każda konto ma osobny dziennik z możliwością dodawania notatek, zmieniania ich treści oraz kasowania dzięki użyciu Firebase Database.

## Screenshots
![Firebase nr1](./Przechwytywanie.JPG)
![Firebase nr2](./Przechwytywanie1.JPG)
![Android APPS nr1](./Przechwytywanie2.JPG)
![Android APPS nr2](./Przechwytywanie4.JPG))
![Android APPS nr3](./Przechwytywanie3.JPG)

## Technologies
* Projekt wykonany w Android Studio
* Firebase Authentication
* Firebase Realtime Database
* JAVA

## Setup
Wymagana wersja do uruchomienia aplikacji to minimum wersja Android 9.0 PIE

## Code Examples
Przykłady implemetacji :

`import android.app.ProgressDialog;`
`import android.content.Intent;`
`import android.os.Bundle;`
`import android.text.TextUtils;`
`import android.view.View;`
`import android.widget.Button;`
`import android.widget.EditText;`
`import android.widget.TextView;`
`import android.widget.Toast;`
`import com.google.android.gms.tasks.OnCompleteListener;`
`import com.google.android.gms.tasks.Task;`
`import com.google.firebase.auth.AuthResult;`
`import com.google.firebase.auth.FirebaseAuth;`
`import com.example.twojalistazadan.Model.Data;`
`import com.firebase.ui.database.FirebaseRecyclerAdapter;`
`import com.google.android.material.floatingactionbutton.FloatingActionButton;`
`import com.google.firebase.auth.FirebaseUser;`
`import com.google.firebase.database.DatabaseReference;`
`import com.google.firebase.database.FirebaseDatabase;`

## Status
Project is: _finished_

## Inspiration
Project inspired by [Google Keep](https://keep.google.com/)

## Contact
Created by **Tomasz Kaszuba** oraz **Mateusz Czepirski**
