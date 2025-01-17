# Awesome Physically Based Rendering

## SIGGRAPH Courses

- [SIGGRAPH 2010 Course: Physically-Based Shading Models in Film and Game Production](http://renderwonk.com/publications/s2010-shading-course/)
- [SIGGRAPH 2012 Course: Practical Physically Based Shading in Film and Game Production](http://blog.selfshadow.com/publications/s2012-shading-course/)
- [SIGGRAPH 2013 Course: Physically Based Shading in Theory and Practice](http://blog.selfshadow.com/publications/s2013-shading-course/)
- [SIGGRAPH 2014 Course: Physically Based Shading in Theory and Practice](https://blog.selfshadow.com/publications/s2014-shading-course/)
- [SIGGRAPH 2015 Course: Physically Based Shading in Theory and Practice](https://blog.selfshadow.com/publications/s2015-shading-course/)
- [SIGGRAPH 2016 Course: Physically Based Shading in Theory and Practice](https://blog.selfshadow.com/publications/s2016-shading-course/)
- [SIGGRAPH 2017 Course: Physically Based Shading in Theory and Practice](https://blog.selfshadow.com/publications/s2017-shading-course/)
- [SIGGRAPH 2020 Course: Physically Based Shading in Theory and Practice](https://blog.selfshadow.com/publications/s2020-shading-course/)
- [SIGGRAPH 2020 Course: Advances in Monte Carlo Rendering](https://sites.google.com/view/legacyofjaroslav)
- [YouTube: SIGGRAPH University](https://www.youtube.com/playlist?list=PLUPhVMQuDB_aWSKj7L_-3Ot_nxBze_YMy)

## Books

- 2018, *Physically Based Rendering:From Theory To Implementation [3rd ed.]*, [**online edition**](http://www.pbr-book.org/), Matt Pharr, Wenzel Jakob, and Greg Humphreys
- 2010, *Physically Based Rendering. From Theory to Implementation [2nd ed.]*, Matt Pharr Greg Humphreys
- 2004, *Physically Based Rendering. From Theory to Implementation [1st ed.]*, Matt Pharr Greg Humphreys
- 1995, *Principles of Digital Image Synthesis*, Andrew S. Glassner
- 1989, *Illumination and Color in Computer Generated Imagery*,  Roy Hall

## Events

- January 2017: Marcos Fajardo(the chief architect of Arnold Renderer), scientific and Engineering award , the Academy of Motion Picture Arts and Sciences
- January 2014: Matt Pharr, Greg Humphreys, and Pat Hanrahan were awarded a [Scientific and Technical Academy Award](https://www.oscars.org/news/19-scientific-and-technical-achievements-be-honored-academy-awardsr) for Physically Based Rendering:   
> Physically based rendering has transformed computer graphics lighting by more accurately simulating materials and lights, allowing digital artists to focus on cinematography rather than the intricacies of rendering. First published in 2004, Physically Based Rendering is both a textbook and a complete source-code implementation that has provided a widely adopted practical roadmap for most physically based shading and lighting systems used in film production.

## A Brief History of Physically Based Rendering

> [The PBR Book, Chapter 1: Introduction](http://www.pbr-book.org/3ed-2018/Introduction/A_Brief_History_of_Physically_Based_Rendering.html)

### Research

![research timeline](./docs/images/research.png)

1. 1981, Microfacet Reflection Models
    - [Cook, R. L., and K. E. Torrance. 1981. A reflectance model for computer graphics. Computer Graphics (SIGGRAPH ’81 Proceedings), 15, 307–16.](https://dl.acm.org/doi/10.1145/357290.357293)

1. 1984, Radiosity
    - [Goral, C. M., K. E. Torrance, D. P. Greenberg, and B. Battaile. Modeling the interaction of light between diffuse surfaces. In Proceedings of the 11th Annual Conference on Computer Graphics and Interactive Techniques (SIGGRAPH ’84), 213–22.](https://dl.acm.org/doi/10.1145/800031.808601)
    - [Cohen, M., and D. P.  Greenberg. The hemi-cube: a radiosity solution for complex environments. SIGGRAPH Computer Graphics 19 (3), 31–40.](https://dl.acm.org/doi/10.1145/325334.325171)

1. 1984, Distributed Ray Tracing
    - [Cook, R. L., T. Porter, and L. Carpenter. 1984. Distributed ray tracing. Computer Graphics (SIGGRAPH ’84 Proceedings), 18, 137–45.](https://dl.acm.org/doi/10.1145/800031.808590)

1. 1986, Path Tracing
    - [Kajiya, J. T. 1986. The rendering equation. In Computer Graphics (SIGGRAPH ’86 Proceedings), 20, 143–50.](https://dl.acm.org/doi/10.1145/15922.15902)

1. 1990s, Monte Carlo–Based Efforts
    - [Arvo, J., and D. Kirk. 1990. Particle transport and image synthesis. Computer Graphics (SIGGRAPH ’90 Proceedings) 24 (4), 63–66.](https://dl.acm.org/doi/10.1145/97879.97886)
    - [Shirley, P. 1990. Physically based lighting calculations for computer graphics. Ph.D. thesis, Department of Computer Science, University of Illinois, Urbana–Champaign.](https://dl.acm.org/doi/book/10.5555/124947)
    - [Kirk, D. B., and J. Arvo. 1991. Unbiased sampling techniques for image synthesis. Computer Graphics (SIGGRAPH ’91 Proceedings), Volume 25, 153–56.](https://dl.acm.org/doi/10.1145/122718.122735)
    - [Shirley, P., C. Y. Wang, and K. Zimmerman. 1996. Monte Carlo techniques for direct lighting calculations. ACM Transactions on Graphics 15 (1), 1–36.](https://dl.acm.org/doi/10.1145/226150.226151)
    - [Greenberg, D. P., K. E. Torrance, P. S. Shirley, J. R. Arvo, J. A. Ferwerda, S. Pattanaik, E. P. F. Lafortune, B. Walter, S.-C. Foo, and B. Trumbore. 1997. A framework for realistic image synthesis. In Proceedings of SIGGRAPH ’97, Computer Graphics Proceedings, Annual Conference Series, 477–94.](https://dl.acm.org/doi/10.1145/258734.258914)

1. 1997, Multiple Importance Sampling
    - [Veach, E. 1997. Robust Monte Carlo methods for light transport simulation. Ph.D. thesis, Stanford University.]()

### Production    

![production timeline](./docs/images/production.png)

- [Arnold Renderer](https://www.arnoldrenderer.com/about/)
    - SIGGRAPH 2001, Marcos Fajardo showed images of Arnold render erearly version
    - 2004, Sony Pictures Imageworks licensed the source code to Arnold
    - 2016, acquired by Autodesk, [official announcement](https://www.autodesk.com/campaigns/solid-angle-joins-autodesk)
- [Pixar's RenderMan](https://renderman.pixar.com/)    
    - 2015, rewritten as a path tracer. 

### Real-time renderer

- [Unreal Engine 4](https://www.unrealengine.com/)
- [Blender Eevee](https://wiki.blender.org/wiki/Reference/Release_Notes/2.80/EEVEE)