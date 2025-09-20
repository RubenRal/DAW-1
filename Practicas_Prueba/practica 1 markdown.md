# Index de la practica
1. Encapçalaments
2. Decorar Text
3. Llistats
4. Enllaços i Imatges
5. Codi
6. Taules

## Encapçalaments
### ***Els estem fent servir ara mateix***, es fan servir amb aquesta estructura:
```# Títol de nivell 1 ```

```## Títol de nivell 2 ```

```### Títol de nivell 3  ```
#
Jo personalment també faig servir els (#) sense escriure cap titol per crear una separació

## Decorar text
- ***Text en negreta***  `***text de exemple*** `
- *Text en cursiva* `*text de exemple*`  
###
Nota: No es pot subratllar text, perquè es confondria el text subratllat amb els enllaços.
  
## Llistats
Els llistats es poden fer de diverses maneres, de forma numerada o de forma no numerada, depenent de per que les vols fer sevir

### Si per exeple volem fer un llistat per saber que ha de comprar el nostre germà petit at Mercadona, l'hi hauriem de fer un llistat sense ordre fent ús dels guións
Per exemple: `- Pomes` (***és molt important deixar un espai després del guió, si no, no es veura de forma correcta en el resultat final.***)
- Pomes
- Patates Fregides Congelades 1Kg 
- Nesquick 
- Nestea de Maracuya 
- Soldadura para fusta
#
En canvi, si volguessim dir-li al nostre germà com fregir les patates quan arribi de comprar-les, haurem de fer servir una llista numerada amb els passos a seguir.
1. Escalfar l'oli de la fregidora a 170º-180º
2. Baixar les patates a l'oli
3. Esperar entre 7 i 10 minuts
4. Treure les patates de la fregidora
###
Per fer una llista numerada, s'ha d'escriure en el següent format: `1. `
###
És el numero u (1) seguit d'un punt (.) seguit d'un espai ( )
#
## Enllaços i Imatges
Els enllaços son una mica confusos de fer servir al començament degut al seu format on s'insereixen dos textos pero només se'n veu un.
###
`[text](URL)`
###
***Mira [aquest video](https://www.youtube.com/watch?v=dQw4w9WgXcQ) tan viral per tot el mon*** 
###
Per inserir imatges el format es casi el mateix, pero escribint un signe d'exclamació al començament:
###
`![Alt text](url-de-la-imatge)`
###
### NOTÍCIA D'ULTIMA HORA
### S'ha escapat de l'oficina del sheriff el perillós criminal JOSEY WALES.
###
![Poster de es busca de Josey Wales, interpretat per Clint Eastwood](https://i.pinimg.com/736x/19/71/59/1971594cb1ea0a5681dcf225a15839bc.jpg)
#
#
#
## Codi 
### Per inserir fragments de codi inline, s'utilitza el símbol de la cometa inversa (`). Per blocs de codi més grans, s'utilitzen tres cometes inverses seguides (```). 
Exemple 1: 
###
`cd C:\Users\Usuario\Desktop\SOY DAW`
###
Exemple 2: 
###
```  
Per donar poders de “sudo” locals de Linux haurem de configurar-ho al fitxer sudoers del sistema 
local:
     1. Hem d’accedir al fitxer /etc/sudoers o executar la comanda visudo

     2. Afegir la línia on indiquem el domini i el grup al que li volem atorgar permisos.
        %grup@domini ALL=(ALL:ALL) ALL

    On:

        • grup → és el grup del domini
        • domini → el domini a aplicar els permisos
        • ALL=(ALL) ALL → permisos d’administrador globals (nivell root)
 ```

## Taules
###  Les taules es poden crear utilitzant barres verticals i guions per definir les columnes i les files:
| Columna 1 | Columna 2 |
|-----------|-----------|
| Contingut | Contingut |