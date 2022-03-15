# Vladislav Lipchey

## Contacts
**Instagram:** *@into_the_lungsofhell* 

**Facebook:** *Vladyslav Lypcehy*

**E-mail:** *<vladlipchey05@gmailcom>*

## About myself

My name is Vladislav, im 18 years old. I am a student of **Uzhhorod National University**.

At the university I got acquainted with such programming languages as C++, C#

Java and Python. I consider it my goal to become a web developer, since at the moment 

this is one of the most demanded jobs in the world. In addition, I myself am very 

interested in web development.

## Example program

Below I have attached an example of the code of the tasks that I solved during my studies.

**Handshake**

**N** businessmen gathered at the round table. Before the meeting, they should shake hands at the same time. No businessmen's hands should cross.

Calculate the number of ways they can shake hands. 

**Input** 

Each line contains one even natural number n (2 ≤ n ≤ 50).

**Output**

For each value of **n**, print on a separate line the number of ways n businessmen can shake hands.

### Solution


```

#include<iostream>
#include<vector>
using namespace std;
int main()
{
    int n;
    while (cin>>n) 
    {
        vector <long long> v(n+1);
        v[0] = 1;
        v[1] = 1;
        for (int i = 2; i <= n; i++) 
        {
            for (int j = 0; j < i; j++) 
            {
                v[i] += v[j] * v[i - j - 1];
            }
        }
        cout << v[n/2]<<endl;
    }

}

```

## Education

I took courses in various programming languages, including basic concepts of C ++, 

Python, JavaScript and HTML/CSS. 

At the moment I am studying int the Uzhhorod National University.

## English 

I studied basic English at school and am currently studying professional English at

 university. I can communicate freely on some topics and understand well the speech of 
 
 a person who speaks English. At the university my level of English was rated as B2.


gift spike federal milk early august shrug museum oblige exact muffin rotate