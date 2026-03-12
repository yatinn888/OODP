#include <iostream>
using namespace std;

// Base class
class Employee {
protected:
    int emp_id;
    string emp_name;

public:
    void getEmployee() {
        cout << "Enter Employee ID: ";
        cin >> emp_id;

        cout << "Enter Employee Name: ";
        cin >> emp_name;
    }

    void displayEmployee() {
        cout << "\nEmployee Details" << endl;
        cout << "Employee ID: " << emp_id << endl;
        cout << "Employee Name: " << emp_name << endl;
    }
};

// Derived class
class Manager : public Employee {
private:
    string department;
    double salary;

public:
    void getManager() {
        getEmployee();

        cout << "Enter Department: ";
        cin >> department;

        cout << "Enter Salary: ";
        cin >> salary;
    }

    void displayManager() {
        displayEmployee();

        cout << "Department: " << department << endl;
        cout << "Salary: " << salary << endl;
    }
};

int main() {
    Manager m;

    m.getManager();
    m.displayManager();

    return 0;
}
