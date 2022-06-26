# EDA using Palmer Archipelago (Antarctica) penguin data


Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network.

The goal of this study is to visualize data in different ways and find correlations.

Due citations: Gorman KB, Williams TD, Fraser WR (2014) Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis). PLoS ONE 9(3): e90081. doi:10.1371/journal.pone.0090081.

These data are originally published in: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0090081

### Variables

Let's look at the variables that we have.

![Captura de tela de 2022-06-06 18-43-47](https://user-images.githubusercontent.com/82065199/172254993-e75ea926-bf5b-4968-a3bb-08250c55f802.png)


One can see that our dataset has the penguin's culmen size, flipper size and body mass as quantitative variables. As qualitative variable we have the specie, island (where it comes from) and its sex.

It's also noticeable that the dataset has a few NaN rows, so I dropped these rows.

![Captura de tela de 2022-06-06 18-48-36](https://user-images.githubusercontent.com/82065199/172255077-723c0071-343d-4f59-8e2b-75914858a5fc.png)

### Count of penguins by specie

The dataset has three different kinds of species, the main one is Adelie, followed by Gentoo and then Chinstrap.

![Captura de tela de 2022-06-06 18-50-53](https://user-images.githubusercontent.com/82065199/172255387-c0850631-0eb6-430b-933a-295c0157ca6c.png)

In proportion:

![Captura de tela de 2022-06-06 18-51-00](https://user-images.githubusercontent.com/82065199/172255431-ff032d3c-cfdb-4926-9e72-e98490c19771.png)

### Body mass according to sex

![sex-dist](https://user-images.githubusercontent.com/82065199/175836619-6a4c7975-6d41-4442-a1a1-bf28caa76dbc.png)

Description for male ones:
![Captura de tela de 2022-06-06 18-54-16](https://user-images.githubusercontent.com/82065199/172255713-91542ea4-8259-402e-bdfa-69fc88b9d54d.png)

Description for female ones:
![Captura de tela de 2022-06-06 18-54-25](https://user-images.githubusercontent.com/82065199/172255751-635953b8-a5f5-4657-b228-d286831b80ff.png)

One can understand that there is a considerable difference between female and male body mass. About 25% of male penguins weighs more than the maximum of females penguins.

### Flipper length by sex

![flipper-dist](https://user-images.githubusercontent.com/82065199/175836638-f9a03d24-edc9-4b22-8891-3d1e2670bc42.png)

Another characteristic is that the flipper length is usually bigger for male, no matter the specie.

### Body mass per specie

![mass-dist](https://user-images.githubusercontent.com/82065199/175836674-a8ca9b95-1ee9-4a19-a0a4-1daa3ff274e2.png)

Adelie and Chinstrap have almost similar distribution of body mass. On the other hand, Gentoo specie are usually heavier than the others.
