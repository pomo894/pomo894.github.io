---
layout: post
title: "Ciberseguretat bàsica per a empreses"
date: 2025-11-11
categories: blog
---

## Introducció

La ciberseguretat és essencial per protegir la informació d'una empresa. Encara que no disposis de grans recursos, hi ha pràctiques bàsiques que poden marcar la diferència.  

![Ciberseguretat](https://agora.xtec.cat/inslacetania/wp-content/uploads/usu1045/2021/04/ciberseguridad_en_2020.jpg)


### Elements clau de seguretat

1. **Contrasenyes fortes**  
2. **Actualitzacions constants de sistemes**  
3. **Formació del personal**  

### Exemple de codi: revisió de contrasenyes (pseudo-code)

```python
def comprova_contrasenya(contrasenya):
    if len(contrasenya) < 8:
        return "Contrasenya massa curta"
    if not any(char.isdigit() for char in contrasenya):
        return "Ha de tenir un número"
    return "Contrasenya vàlida"
