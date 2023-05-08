Download Link: https://assignmentchef.com/product/solved-stack-and-the-heap
<br>
<ul>

 <li>Explain the difference between the stack and the heap. Give a code example of malloc and free. List some common memory-related bugs in C programs.</li>

</ul>




<ul>

 <li>Given the following C++ code, improve the code by eliminating length calls out of the loop, put most used variables first when initializing variables, use prefix operators rather than postfix operators, loop unrolling, and any other improvements you would like to make to improve performance. Please note, the order of the output is not important, all data should be output. #include &lt;iostream&gt;#include &lt;vector&gt;#include &lt;string&gt;using namespace std;int main(int argc, char* argv[]) {double sum=0;vector&lt;double&gt; price;vector&lt;string&gt; game;vector&lt;string&gt; designer; push_back(53.41);game.push_back(“Carcassone”);designer.push_back(“Wrede”);price.push_back(46.51);game.push_back(“Agricola”);designer.push_back(“Rosenberg”);price.push_back(31.02);game.push_back(“Puerto Rico”);designer.push_back(“Seyfarth”); for(int i=0;i&lt;game.size();i++){cout&lt;&lt;game[i]&lt;&lt;“t”&lt;&lt;endl;}cout&lt;&lt;endl;for(int i=0;i&lt;designer.size();i++){cout&lt;&lt;designer[i]&lt;&lt;“t”&lt;&lt;endl;}cout&lt;&lt;endl;cout&lt;&lt;price[0]&lt;&lt;“t”&lt;&lt;endl;cout&lt;&lt;price[1]&lt;&lt;“t”&lt;&lt;endl;cout&lt;&lt;price[2]&lt;&lt;“t”&lt;&lt;endl;sum=price[0]+price[1]+price[2];cout&lt;&lt;“The total price for all games is “&lt;&lt;sum&lt;&lt;endl;cin.ignore();return 0;}</li>

</ul>