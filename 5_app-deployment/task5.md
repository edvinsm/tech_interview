# Apraksts
Tika pacelts Nginx web servera Kubernetes deployments ar konkrētu konfigurāciju, Kubernetes klāsterī ir konfigurēts Nginx ingress.

## Uzdevums
1) Kā konfigurēt Nginx web servera deployment, lai tiktu pacelti 3 replikas podi.
2) Podu replikām jādarbojās katrai uz savas nodes, lai netiktu paceltas 2 podu replikas uz vienas nodes.
3) Kā novērst situāciju, kad  paaugstinātas slodzes gadījumā,  Nginx web servera pods negatīvi ietekmē klāstera nodes darbību jeb veiktspēju.
4) Kā mēs varam konfigurēt piekļuvi pie Nginx web servera uz ārpusi, ja uz klāstera nav instalēts ingress?
