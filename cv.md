# Nadezhda Anisimova
***  
## Contact information:  
**Location:** Moscow, Russia  
**E-mail:** anyh0pe@yandex.ru  
**Telegram:** @anyhhope  
**Github:** [anyhhope](https://github.com/anyhhope)

***  

## Briefly About Myself:
I'm a second-year student of University MISIS majoring in Informatics and Computer engineering, *Intelligent Systems for Data Analysis*. This semester having only algorithms to study, I feel the huge need to explore other possibilities in IT. Frontend Development will allow me to implement all ideas I have, being keen on visualisation and practical use.  

I'm a quick, inquiring and efficient student, entered University with no IT background, now I'm earning best scores. I hope my exploration of Frontend Development will be successful.  

***  

## Skills:
* C++  
* Python (basic knowledge)  
* Git, Github  
* VS Code, IntelliJ IDEA

***  

## Code example:
The C++ implementation of searching several substrings in original string in trie:
```
for(int j = 0; j < line.length(); j++){
        node *cur_v = root;
        for (int i = j; i < line.length(); i++) {
            char c = line[i];
            if( cur_v->next[c - 'a'] != nullptr) {
                if(cur_v->next[c - 'a']->strings != -1) ans[cur_v->next[c - 'a']->strings] = 1;
            }
            else{
                break;
            }
            cur_v = cur_v->next[c - 'a'];
        }
    }
```

***  

## Education:
* **University MISIS:** Informatics and Computer engineering major, *Intelligent Systems for Data Analysis* speciality (second year)  
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

***  

## Languages:
English - C1   
Spanish - A1  
Russian - native
