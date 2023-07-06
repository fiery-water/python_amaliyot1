# python_amaliyot1
Assalomu alaykum dasturlash olami vakillari bu mening GitHup ga yuklayotgan birinchi kodim
hali ko'plab dasturlar tuzmoqchiman meni qo'llab quvvatlab turishingizni sizlardan so'ra qolaman
Anvar Narzullayev akaga kattakon raxmat aytib qolaman

shaxslar={"Abu Abdulloh Muhammad ibn Ismoil":[810,870,"buxoro"],"Abdulla Qodiriy":[1894,1938,"toshkent"],"Erkin Vohidov":[1936,2016,"farg'ona"],
          "Alisher Navoiy":[1441,1501,"xirot"]}
for ism,ruyxat in shaxslar.items():
    t_yil=ruyxat[0]
    umr=ruyxat[1]-ruyxat[0]
    t_joy=ruyxat[2]
    print(f"{ism.title()} {t_yil}-yilda {t_joy.title()}da tavallud topgan . {umr} umir ko'rgan ")
mashhurlar={"Abu Abdulloh Muhammad ibn Ismoil":["Al-jome' as-sahih","Al-adab al-mufrab",
                                                "Al-tarix al-kabir","Al-tarix al-sag'ir"],
            "Abdulla Qodiriy":["O'tgan kunlar","Mehrobdan Chayon","Obid ketmon"],
            "Erkin Vohidov":["Tong nafasi","Qushiqlarim sizga","O'zbegim","Qiziquvchan Matmusa"],
            "Alisher Navoiy":["Xamsa","Lison ut-Tayr","Mahbub Al-Qulub","Munojat"]}
for ism,asarlar in mashhurlar.items():
    print(f"{ism}ning asarlari:")
    for asar in asarlar:
        print(asar, ",",end=' ')
