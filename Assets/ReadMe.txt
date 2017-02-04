Tva e bazova scena s animaciq.

Ochevidnia problem e, che camerata e statichna, i neizbejno nashia geroi izliza ot pogleda ni.

Triabvat mi 2 neshta:
	1. Camerata da stoi na edno miasto, no da zavyrta i da sledi geroia.
	2. Da imame kontrol s klaviaturata vyrhu poziciata na kamerata (da ia mestim napred-nazad, vliavo-vdiasno)
	3. Kamerata da sledva geroia (kogato toi se otdaliechava ot kamerata tia da zapochva da se dviji plavno s nego za da poddyrja distancia)
	
Ako zapochnesh da se borish s tova, shte vidish che ima razni tynkosti v cialata rabota:
	1. Ako kamerata sledi choveka, i toi pravi byrzi dvijenia, camerata pochva da se dviji tvyrde byrzo i tova drazni. Zatova triabva da ima niakakvo omekotiavane na dvijenieto na kamerata (v Unity ima poniatie "lerp". Syshtoto vaji za dvijenia nagore nadolu,  ako choveka podskacha i se navejda - koia chast ot nego sledim? I kolko plavno?
	2. Tuk problema e che ne e trudno da se napravi kamerata da se dviji naliavo-nadiasno, no tia go pravi v "world space". A za da e intuitivno za usera, triabva da e v "local space".
	3. Tuk veche stava syvsem got, zashtoto algorityma triabva da sychetava vyrtene v posoka na geroia s translacia za da poddyrja distancia do geroia, vyrhu koiato se naslagva translacia po komanda ot usera - i vscihko tova da e lerp-nato za da se sluchva plavno :)
	
	enjoy!