# Makeeva Yana 
## Student VSU named after P.M.Masherov
### Speciality: information systems manager
***
## Contact information
**email:** makeeva.yana04@gmail.com       
**phone:** +375(33)3242397         
**telegram** @makesha_04       
 ## Briefly about myself            
My acquaintance with information technology, programming and economics began in September 2021.  I like to learn and learn new things. At first I may be afraid of difficulties, but in the end I cope with them - this is a kind of challenge for me. I like to work in a team and easily find an approach to people. I am sociable, responsible. I like to exchange some useful skills with colleagues.         
 ## Skills         
 - C++
 - Theory and simple codes on Accembler
 - Adobe Photoshop, Inskape
 - Microsoft World, Excel, Access 
 ***
 ## Code example:
 It is necessary to develop a program that includes all the data and operators(<<,>> etc.) necessary for solving the problem.Provide for the handling of exceptional situations. Find the sum and difference of two multi-valued integers.

```c++

class Cislo
{
private:
 int x;
public:
 Cislo(int X) { x = X; }
 Cislo() { x = 0; }
 friend std::ostream& operator<< (std::ostream& out, const Cislo& d1);
 friend std::istream& operator>> (std::istream& in, Cislo& d1);
 friend Cislo operator+(const Cislo& d1, const Cislo& d2);
 friend Cislo operator-(const Cislo& d1, const Cislo& d2);

 int getX() const
 {
  return x;
 }
};

std::ostream& operator<< (std::ostream& out, const Cislo& d1)
{
 out /*<< "Одно из чисел="*/ << d1.getX() << endl << endl;

 return out;
}

std::istream& operator>> (std::istream& in, Cislo& d1)
{
 cout << "Введите одно из многозначных чисел " << endl;
 in >> d1.x;
 cout << endl; 

 if (d1.x < 9  && d1.x > -9)
 {
  cout << "Введено однозначное число" << endl<<endl;
  system("pause");
  exit(1);
 }
 return in;
}
Cislo operator+(const Cislo& d1, const Cislo& d2)
{
 return Cislo(d1.x + d2.x);
}
Cislo operator-(const Cislo& d1, const Cislo& d2)
{
 return Cislo(d1.x - d2.x);
}
int main()
{
 SetConsoleOutputCP(1251);
 SetConsoleCP(1251);
 Cislo X1;
 Cislo X2;
cin >> X1;
cin >> X2;
 Cislo Sum = X1 + X2;
 Cislo Raz = X1 - X2;
cout << "Сумма этих чисел=" << Sum;
cout << "Разность этих чисел=" << Raz;
```
## English level:
**B1**
## Courses:
- Streamline language school, a 144-hour **English for Teens** course at Intermediate+ level
