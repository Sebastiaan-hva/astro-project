Astro basic installatie gedaan en  de documentatie gelezen.

https://docs.astro.build/en/install-and-setup/

het is in astro mogelijk om andere templates/frameworks te gebruiken.
https://docs.astro.build/en/install-and-setup/
File structure lijkt redelijk op Svelte alleen hier kan je wel pages eigen names geven ipv dat ze allemaal dezelfde naam hebben.
Je kan dus makkelijk astro combineren met andere frameworks als je een van de features van astro wilt gebruiken.

Astro heeft een eigen dev toolbar onderaan elke pagina in je dev omgeving. Hierin zitten tools om je site te debuggen.
De toolbar bevat toegang tot de astro docs, de github repo & discord. je hebt een insepct die info geeft over de islands van de huidige pagina. en je hebt een audit button die een aantal tests doet voor performance en A11LY.

Astro heeft een new frontend architectuur patroon dat "Islands Architecture" heet. 
Islands zorgen ervoor dat eerst alle statische HTML gerenderd wordt en dat daarna pas de Javascript in delen ingeladen wordt. Dit zorgt ervoor dat de website niet in 1x alle javascript aan het begin hoeft in te laden. Dit zorgt ervoor dat Astro in sneller werkt dan sommige andere JS frameworks.
hier meer over islands (https://docs.astro.build/en/concepts/islands/#what-is-an-island).

Ik vind zelf de Astro documentatie duideljk en er zijn genoeg tutorials.
