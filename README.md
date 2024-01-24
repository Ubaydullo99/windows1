# windows1
## tables of contents 

* [win10Setup](#win10setup)
* [kaggle](#kaggle)
* [etc](etc)


## win10Setup
win10 iso installer = https://www.microsoft.com/ko-kr/software-download/windows10

- Boot the computer from a DVD or USB drive.
- Press Shift + F10 in Windows Setup to open the command prompt.

  
Type the following commands in the correct order: 

    Diskpart
    list disk
    select disk <number> (replace <number> with the disk you want to clean)
    clean
    convert mbr
    create partition primary
    format fs=ntfs quick
    assign letter=<letter> (replace <letter> with the drive letter you want to assign)
    exit


## kaggle

https://www.kaggle.com/discussions/questions-and-answers/210493 Kaggle python version edit

https://www.kaggle.com/discussions/questions-and-answers/210493

https://www.kaggle.com/code/blinkthink/change-python-version-on-kaggle

https://www.kaggle.com/code/taylorsamarel/change-python-version-on-kaggle-taylor-amarel



## etc


win11 supported processors = https://learn.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-intel-processors
