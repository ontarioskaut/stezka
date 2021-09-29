# Skautská stezka
webová aplikace pro jednoduché plnění skautské stezky
- a Tom tady může přidávat také

## Plánovné featury
- patroni
- tvoření vlastního plánu plnění
- schvalování
- virtuální odměny (odznáčky)
- ukazatel progressu
- design podle ostatních skautských projektů

## Poznámky
- aplikace používá Flask framework 
- v našem nasazení používáme gunicorn WSGI server a nginx ([tady](https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-18-04) mají hezký návod)
- používáme [Oracle cloud Allways free compute instances](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm), určité prostředky by měly být zdarma dostupné i po vypršení testovacího období. Pro registraci ale potřebujete kreditní kartu
