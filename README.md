# hse_hw2_chip
Bioinformatics 4 semester 2 homework


---

В качестве варианта задания мной были выбраны следующие данные:  
Клеточная линия: *IMR-90*, гистоновая метка: *H3K79me1*  

[Ссылка на colab-ноутбук](https://colab.research.google.com/drive/16n4yU4DZD2eOGZHa5bU8bRSS3pLQSx7l?usp=sharing)  

## Сравнение FastQC  

Приведем фото до подрезаний и после для каждого файла:  

ENCFF394HYQ изначально:  

<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/HYQ1.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/HYQ2.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/HYQ3.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/HYQ4.PNG width=500/>  

ENCFF394HYQ после подрезаний:  

<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/HYQ_trimmed1.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/HYQ_trimmed2.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/HYQ_trimmed3.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/HYQ_trimmed4.PNG width=500/>  

Кажется, что изначальное качество было лучше (например из *per title sequence quality*), так что подрезание здесь не сильно нужно было, однако картину оно не сильно ухудшило.  

ENCFF187NVD изначально:  

<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/NVD1.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/NVD2.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/NVD3.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/NVD4.PNG width=500/>  

ENCFF187NVD после подрезаний:  

<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/NVD_trimmed1.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/NVD_trimmed2.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/NVD_trimmed3.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/NVD_trimmed4.PNG width=500/>  

В данном случае оба отчета примерно одинаковые (хорошие), так что подрезания можно было тоже не делать  

ENCFF282SBH изначально:  

<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/SBH1.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/SBH2.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/SBH3.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/SBH4.PNG width=500/>  

ENCFF282SBH после подрезаний:  

<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/SBH_trimmed1.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/SBH_trimmed2.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/SBH_trimmed3.PNG width=500/>  
<img src=https://github.com/TheMostKnown/hse_hw2_chip/blob/main/images/SBH_trimmed4.PNG width=500/>  

В данном случае, как раз, хорошо видно (особенно по *per base sequence quality*), что подрезание необходимо, чтобы сделать рид лучше.  

## Статистика по выравниваниям:  


