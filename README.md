class biodata{
    private:
        string name;
        int age;
        string tach_stack;
    public:
        biodata(string name, int age, string tach_stack){
            this->name = name;
            this->age = age;
            this->tach_stack = tach_stack;
        }
    
    void display(){
        cout << "Name: " << name << endl;
        cout << "Age: " << age << endl;
        cout << "Tach Stack: " << tach_stack << endl;
    }

};

int main() {
    
    biodata biodata1("Yusran Abdulah", 25, "C++, Javascript, Tailwind");

    biodata1.display();

    return 0;
}
