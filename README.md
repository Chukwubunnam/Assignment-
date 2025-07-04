# Assignment-
Declare a static array of size 10 populate the user input print all value using java and c++
System.out.println("Enter 10 integers:");
    for (int i = 0; i < 10; i++) {
        arr[i] = sc.nextInt(); // Populate from user input
    }

    System.out.println("You entered:");
    for (int i = 0; i < 10; i++) {
        System.out.print(arr[i] + " ");
    }
}
cout << "Enter 10 integers:" << endl;
for (int i = 0; i < 10; ++i) {
    cin >> arr[i]; // Populate from user input
}

cout << "You entered:" << endl;
for (int i = 0; i < 10; ++i) {
    cout << arr[i] << " ";
}
cout << endl;
return 0;
