# schskillchain(ssc)
- usage

  Open Liquefacrion(溶解)

        //ssc f o


- commnad

  - //ssc skillchain order [sc_tier] [mb] [mb_tier]

    skillchain = f[fire],b[blizzard],a[aero],s[stone],t[thunder],w[water],l[light],d[dark],f2[fire2],b2[blizzard2],a2[aero2],s2[stone2],t2[thunder2],w2[water2],l2[light2],d2[dark2]

    order = o[open],c[close],a[all] (all = both open and close)

    sc_tier = 1,2,3,4,5,h,h2

    mb (cast elemental magic or helix after skillchain)

    mb_tier = 1,2,3,4,5,h,h2

- settings.xml
  - wait:

    immanence_wait: waiting time after use immanence

    skillchain_wait: waiting time between skillchan (when order = all)

    skillchain_wait_helix: waiting time between opening and closing if spell opening skillchain were helix (when order = all)

    mb_wait: casting waiting time of casting mb spell after skillchain 

    mb_wait_helix: waiting time of casting mb spell afert helix skillchain

  - target:

    type: spell target (e.g. t or bt)

  - auto_dark_arts:
  
    use dark arts if you don't use dark arts.