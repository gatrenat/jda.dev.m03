#####################################
Anotacions sobre múltiples instàncies
#####################################

* Autor/a: XXX

* Data: XXX

Introducció
===========

En aquest exercici incloc les meves anotacions sobre el tema de *múltiples
instàncies* dins de la *programació orientada a objectes*.

Les anotacions responen a diferents preguntes sobre aquest codi:

::

    01    public class GatRenat {
    02        public int vides = 7;   // vides disponibles del gat Renat

    03        public static void main(String[] args) {
    04            GatRenat renatI;
    05            renatI = new GatRenat();               // crea un primer gat Renat
    06            System.out.println("El gat Renat I té  " + renatI.vides + " vides");

    07            GatRenat renatII = new GatRenat();     // crea un segon gat Renat!
    08            System.out.println("El gat Renat II té " + renatII.vides + " vides");

    09            renatI.vides++;
    10            System.out.println("El gat Renat I té  " + renatI.vides + " vides");
    11            System.out.println("El gat Renat II té " + renatII.vides + " vides");

    12            renatII = renatI; // atenció: la instància de Renat II es perd!
    13            System.out.println("El gat Renat I té  " + renatI.vides + " vides");
    14            System.out.println("El gat Renat II té " + renatII.vides + " vides");

    15            renatI.vides++;
    16            System.out.println("El gat Renat I té  " + renatI.vides + " vides");
    17            System.out.println("El gat Renat II té " + renatII.vides + " vides");
    18        }
    19    }

Pregunta 1. Sortida
===================

La sortida en executar el programa anterior és:

::

    $ java GatRenat
    XXX

Pregunta 2. Memòria
===================

La memòria que ocupa, com a mínim, una instància de ``GatRenat`` és XXX.

Baso els meus càlculs en XXX.


Pregunta 3. Fins la línia 5
===========================

El nombre d'instànces de ``GatRenat`` tot just executat el codi fins la línia 5 (inclosa) és XXX

Pregunta 4. Fins la línia 6
===========================

El nombre d'instànces de ``GatRenat`` tot just executat el codi fins la línia 6 (inclosa) és XXX

Pregunta 5. Fins la línia 9
===========================

El nombre d'instànces de ``GatRenat`` tot just executat el codi fins la línia 9 (inclosa) és XXX

Pregunta 6. Vides iguals a 7 i 10
=================================

Les línies 7 i 10 mostren les mateixes vides pels gats Renat I i Renat II,
perquè XXX

Pregunta 7. Vides diferents a 13 i 14
=====================================

Les línies 13 i 14 mostren diferent nombre de vides pels gats Renat I i
Renat II, perquè XXX

Pregunta 8. El comentari de la línia 16
=======================================

Penso que el comentari de la línia 16 vol dir XXX

Pregunta 9. Vides iguals a 17 i 18
==================================

Les línies 17 i 18 mostren les mateixes vides pels gats Renat I i Renat
II, perquè XXX

Pregunta 10. Vides iguals a 21 i 22
===================================

Les línies 21 i 22 mostren les mateixes vides pels gats Renat I i Renat II
malgrat la instrucció de la línia 20, perquè XXX

Pregunta 11. Nombre d'instàncies
================================

El nombre d'instàncies hi ha quan s'executa la línia 20 és XXX

La raó és XXX

