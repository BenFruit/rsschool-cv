# __Pirzhanov Yerassyl__  
### Contact info:  
* Phone number: **+7(705)599-20-65** _or_ **+7(705)599-20-66**  
* Email: erasil200270@gmail.com
* Instagram: @lookingforyoumysweety
* Discord: @BenFruit
### Profile
*I am 17 years old young developer from Kazakhstan. Programming for me is something that helps me to express myself. I strongly believe that accuracy and quality of person's code shows personality of him or her. So it is very important for me to write fast and optimized code. Aslo I am student of Nazarbayev Intellectual School of Physics and Mathematics, and now working with project based on neural network and going to participate at Infomatrix - 2020 this year. Three essential characteristics for me is:*
* **responsibility**
* **time-management**
* **communication**
### Skills
- [x] Advanced usage of the C++
- [x] Medium level of the C#
- [x] Mastered the Python
- [ ] Few experience with HTML and CSS
### Latest Code Examples on "C++"</br>
#### Solution for "1295-A"
```C++
#include <iostream>
#include <math.h>
#include <cmath>
using namespace std;
int main() {
  int q;
  bool b = 0;
  cin>>q;
  for(int k = 0; k < q; k++)
  {
    int n;
    cin>>n;
    int a[n];
    for(int i = 0; i < n; i++)
    {
      cin>>a[i];
    }
    for(int i = 0; i < n-1; i++)
    {
      for(int j = i + 1; j < n; j++)
      {
        if(abs(a[i] - a[j]) == 1)
        {
          b = true;
          break;
        }
      }
    }
    cout<<1 + b<<endl;
    b = 0;
  }
}

```
#### Solution for school competetion's task
##### Specification
Садовод Лёша преподаёт школьникам олимпиадную информатику. На день учителя ребята подарили ему набор деревянных палочек, каждая из которых представляет собой отрезок целочисленной длины. Теперь Лёша хочет вырастить из них дерево.  

Дерево представляет собой ломаную на плоскости, состоящую из всех подаренных ему палочек. Ломаная начинается в точке (0,0). Строя ломаную, Лёша может присоединять палочки в любом порядке, располагая каждую горизонтально или вертикально (то есть параллельно оси OX или OY). При этом не разрешается, чтобы две подряд идущие палочки лежали одновременно горизонтально или вертикально. Смотрите картинки ниже для уточнения деталей.  

Лёша хочет сделать так, чтобы конец ломаной был как можно дальше от точки (0,0). Помогите ему вырастить дерево таким образом!  

Заметим, что ломаная, в форме которой Леша вырастит дерево, может иметь самопересечения и самокасания, однако можно доказать, что оптимальный ответ не содержит ни самопересечений, ни самокасаний.
##### Solution
```C++
#include <iostream>
#include <algorithm>
using namespace std;
int main() {
  long long int n,f =0 ,s =0;
  cin>>n;
  long long int a[n];
  for(long long int i = 0; i < n;i++)
  {
    cin>>a[i];
  }
  sort(a,a+n);
  
  for(long long int i = 0; i < n/2; i++)
  f += a[i];
  for (long long int i = n/2; i < n; i++)
  s += a[i];
  cout<<(f*f) + (s*s);
}
```
#### (from contests on codeforces.com)
### Experience
I have participated in local,regional,republican and national programming competetions. Have experience with 3-d modeling on the "Blender", also can create simple videogames using "Unity"
### Education
Studying in the NIS of Physics and Math with choosen course of advanced computer science
### English
Since the 7th grade, I have had English lessons for 8 hours a week, including lessons of native speakers who work as teachers in my school. And starting from this year all natural science lessons, examinations taked with participation of foreign teachers. Basically I have practicing my English everyday 8 hours a day. My level of English is between **C1** and **C2**
