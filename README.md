<!--This Markdown contain file-->

__F__~~i~~`l`_e_
---

### To write something in a file
<ul type="square">
<li> fputc()
<li> fputw()
<li> fputs()
<li> fprintf()
<li> fwrite()
</ul>

### To read something in a file

<ul type="square">
<li> fgetc()
<li> fgetw()
<li> fgets()
<li> fscanf()
<li> fread()
</ul>

### open and close file

```c
#include<stdio.h>
int main()
{
    FILE *file;

    file = fopen("test.txt","w");

    if(file==NULL)
    {
        printf("file doesn't exist");
    }
    else
    {
        printf("file created");
        fclose(file);
    }
    getch();
}
```

<image src="./images/openclose.png" border="5" hspace="10" vspace="10" alt="file not found" align="top" title="print" height="100" width="300"/>

</br>
<image src="./images/location.png"/>

