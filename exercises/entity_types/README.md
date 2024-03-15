<h2 align=center>Week 8: <em>In-Class Exercise</em></h2>

<h1 align=center>Exercise: <em>Entity Types</em></h1>

<h3 align=center>15 Lone Moon, Imperial Year MMXXIIV</h3>

### Instructions

Using the enum [**`EntityType`**](SDLProject/Entity.h) and the `Entity` class's `m_is_active` and `m_type` attributes, write code that will make a random platform disappear when our player steps on it:

![example](assets/example.gif)

<sub>**Figure 1**: Desired behaviour.</sub>

Note that you'll have to copy the code from not just [**`main.cpp`**](SDLProject/main.cpp), but also [**`Entity.h`**](SDLProject/Entity.h) and [**`Entity.cpp`**](SDLProject/Entity.cpp) to be in the same starting point as me. Also, in order to generate a random integer from 0 to `limit` in C++, one needs to do the following:

```cpp
#include <cstdlib>

int main()
{
    int limit = 100;
    int random_int = rand() % limit;

    return 0;
}
```

---

The solution can be found [**here**](SDLProject/solution/main.cpp), [**here**](SDLProject/solution/Entity.cpp), and [**here**](SDLProject/solution/Entity.h).
