## Cloth simulation till 2007

### Research problems in clothing simulation
Choi K J, Ko H S. Research problems in clothing simulation[J]. Computer-aided design, 2005, 37(6): 585-592.

	1. Simulation model
		a. First
			Demetri Terzopoulos, John Platt, Alan Barr, Kurt Fleischer. Elastically deformable models. Proceedings of the 14th annual conference on computer graphics and interactive techniques.: ACM Press; 1987 p. 205–214.
		b. Refine with damping and collision handling
			Michel Carignan, Ying Yang, Nadia Magnenat-Thalmann, Daniel Thal-mann. Dressing animated synthetic actors with complex deformable clothes. Comput Graph (Proc ACM SIGGRAPH 92).: ACM; 1992 p. 99–104.
		c. Non-continuum model
			Breen David E, House Donald H, Wozny Michael J. Predicting the drape of woven cloth using interacting particles. Proceedings of SIGGRAPH 94, computer graphics proceedings, annual conference series.: ACM Press/ACM SIGGRAPH; 1994 p. 365–372.
			Bernhard Eberhardt, Andreas Weber, Wolfgang Strasser. A fast, flexible, particle-system model for cloth draping. IEEE Comput Graph Appl 1996;16(5):52–9.
		d. Elastic method
			Pascal Volino, Martin Courshesnes, Nadia Magnenat Thalmann. Versatile and efficient techniques for simulating cloth and other deformable objects. Proceedings of SIGGRAPH 95, computer graphics proceedings, annual conference series.: ACM Press/ACM SIG-GRAPH; 1995 p. 137–144.
		e. Shell theory with standard FEM
			Eischen Jeffrey W, Shigan Deng, Clapp Timothy G. Finite-element modeling and control of flexible fabric parts. IEEE Comput Graph Appl 1996;16(5):71–80.
	2. Numerical
		a. Semi-implicit
			i. David Baraff, Andrew Witkin. Large steps in cloth simulation. Proceedings of SIGGRAPH 98, computer graphics proceedings, annual conference series.: ACM, ACM Press/ACM SIGGRAPH; 1998 p. 43–54.
		b. Simple hessian matrix
			Mathieu Desbrun, Peter Schro¨der, Alan Barr. Interactive animation of structured deformable objects. Graph Interf 1999 p. 1–8.
		c. Avoid computational
			Young-Min Kang, Jeong-Hyeon Choi, Hwan-Gue Cho, Chan-Jong Park. Fast and stable animation of cloth with an approximated implicit method. Comput Graph Int 2000 p. 247–256.
	3. Buckling problem
		Kwang-Jin Choi, Hyeong-Seok Ko. Stable but resposive cloth. SIGGRAPH 2002 conference proceedings, annual conference series.: ACM Press/ACM SIGGRAPH; 2002 p. 604–611.
	4. Collision 
		a. Detection
			Stefan Gottschalk, Ming Lin, Dinesh Manocha. OBB-Tree: a hierarchical structure for rapid interference detection. SIGGRAPH 96 conference proceedings, annual conference series, held in New Orleans, Louisiana, 04–09 August.: ACM SIGGRAPH, Addison Wesley; 1996 p. 171–180.
			Klosowski James T, Mitchell Joseph SB, Henry Sowizral, Karel Zikan. Efficient collision detection using bounding volume hierarchies of k-DOPs. IEEE Trans Vis Comput Graph 1998;4(1):21–36.
		b. Subdivision
			Matthew Moore, Jane Wilhelms. Collision detection and response for computer animation. Comput Graph (SIGGRAPH’88 Proc) 1988 p. 289–298.
			Smith A, Kitamura Y, Takemura H, Kishino F. A simple and efficient method for accurate collision detection among deformable objects in arbitrary motion. Proceedings of the IEEE virtual reality annual international symposium 1995 p. 136–145.
			Greg Turk. Interactive collision detection for molecular graphics. Master’s thesis. Department of Computer Science, University of North Carolina at Chapel Hill; 1989.
			Zhang D, Yuen M. Collision detection for clothed human animation. Proceedings of the 8th Pacific graphics conference on computer graphics and application (PACIFIC GRAPHICS-00); October 3–5 2000 p. 328–337.
		c. Space-time 4D collision space
			Ming C. Lin, Dinesh Manocha, John Canny. Fast collision detection between geometric models. Technical Report TR93-004, Department of computer science, University of North Carolina at Chapel Hill; 1993.
			Tom Duff. Interval arithmetic and recursive subdivision for implicit functions and constructive solid geometry. SIGGRAPH’92: 19th international conference on computer graphics and interactive techniques, Chicago, Illinois, July 26–31.: ACM Press; 1992 p. 131–138.
			Hubbard Philip M. Collision detection for interactive graphics applications. IEEE Trans Vis Comput Graph 1995;1(3):218–30. Hubbard Philip M. Collision detection for interactive graphics applications. IEEE Trans Vis Comput Graph 1995;1(3):218–30.
			Sigal Raab. Controlled perturbation for arrangements of polyhedral surfaces with application to swept volumes. Proceedings of the conference on computational geometry (SCG’99), New York, NY, June 13–16.: ACM Press; 1999 p. 163–172.
		d. Geo collision
			Pascal Volino, Nadia Magnenat Thalmann. Accurate collision response on polygonal meshes. Comput Animat 2000.
		e. Rigid impact zone
			Xavier Provot. Collision and self-collision handling in cloth model dedicated to design garments. Graph Interf’97 1997 p. 147–154.
			Suejung Huh, Dimitris Metaxas, Norman Badler. Collision resolutions in cloth simulation. Comput Animat 2001.
		f. Robust: repulsive force + geo-collision + rigid impact zone + subdivision
			Robert Bridson, Fedkiw Ronald P, John Anderson. Robust treatment of collisions, contact, and friction for cloth animation. SIGGRAPH 2002 conference proceedings, annual conference series.: ACM Press/ACM SIGGRAPH; 2002 p. 594–603.


### Advanced Topics in Virtual Garment Simulation Part 1
THOMASZEWSKI, B., WACKER, M., STRAER, W., LYARD, E., LUIBLE, C., VOLINO, P., KASAP, M., MUGGEO, V., AND MAGNENAT-THALMANN, N. 2007. Advanced topics in virtual garment simulation. In Eurographics 2007 - Tutorials, 795–855.
(reference to "Key Techniques for Interactive Virtual Garment Simulation." which is More comprehension)

	1. Simulation model
		a. Mass-spring model
			i. First
				1) PROVOT X.: Deformation constraints in a mass- spring model to describe rigid cloth behavior. In Proceed- ings of Graphics Interface (GI 1995) (1995), Canadian Computer-Human Communications Society, pp. 147– 154.
			ii. More generic
				1) BREEN D., HOUSE D., WOZNY M.: Predicting the drape ofwoven cloth using interacting particles. In Proceedings of ACMSIGGRAPH ’94 (1994),ACMPress, pp. 365–372
				2) EBERHARDT B., WEBER A., STRASSER W.: A fast, flexible, particle-system model for cloth draping. IEEE Computer Graphics and Applications 16, 5 (Sept. 1996), 52–59.
				3) VOLINO P., COURCHESNE M., MAGNENAT- THALMANN N.: Versatile and efficient techniques for simulating cloth and other deformable objects. In Proceedings of ACM SIGGRAPH ’95 (1995), ACM Press, pp. 137–144.
		b. Continuum mechanics
			i. Most based on geometrically exact thin shell formulation presented
				SIMO J. C., FOX D. D., RIFAI M. S.: On a stress resultant geometrically exact shell model. part i: Formulation and optimal parametrization. In Computa- tional Methods in Applied Mechanics and Engineering (1989), vol. 72, pp. 267–302.
			ii. Buckling --> divergence
			iii. Linear FE plane-stress assumption
				1) ETZMUSS O., KECKEISEN M., STRASSER W.: A Fast Finite Element Solution for Cloth Modelling. In Proceedings of Pacific Graphics (2003), pp. 244–251.
			iv. Subdivision
				1) Co-rotational strain formulation
					CIRAK F., ORTIZ M., SCHRÖDER P.: Sub- division surfaces: A new paradigm for thin-shell finite- element analysis. Journal for Numerical Methods in En- gineering 47 (2000), 2039–2072.
				2) Extension
					a) THOMASZEWSKI B., WACKER M., STRASSER W.: A consistent bending model for cloth simulation with corotational subdivision finite elements. In Proceedings of ACMSIGGRAPH/Eurographics Symposium on Computer Animation (SCA 2006) (2006), Eurographics Association, pp. 107–116.
		c. Middle course between FE and MS
			VOLINO P., MAGNENAT-THALMANN N.: Accurate garment prototyping and simulation. Computer- Aided Design & Applications 2, 5 (2005), 645–654.
	2. Numerical time integration
		a. Survey
			i. HAUTH M., ETZMUSS O.: A High Performance Solver for the Animation of Deformable Objects using Advanced Numerical Methods. In Computer Graphics Forum (2001), pp. 319–328.
			ii. VOLINO P., MAGNENAT-THALMANN N.: Comparing efficiency of integration methods for cloth simulation. In Proceedings of Computer Graphics International 2001 (CGI 2001) (2001), IEEE Computer Society, pp. 265–274.
		b. Implicit
			i. BARAFF D., WITKIN A.: Large steps in cloth simulation. In Proceedings of ACM SIGGRAPH ’98 (1998), ACM Press, pp. 43–54.
	3. Collision handling
		a. Bound volume hierarchy BVH
			i. AABB
				1) LARSSON T., AKENINE-MÖLLER T.: Colli- sion detection for continuously deforming bodies. Pro- ceedings of Eurographics ’01 (2001), 325–333
			ii. Generic discrete oriented polytopes (k-DOPs)
				KLOSOWSKI J. T., HELD M., MITCHELL J. S. B., SOWIZRAL H., ZIKAN K.: Efficient colli- sion detection using bounding volume hierarchies of k-DOPs. IEEE Transactions on Visualization and Computer Graphics 4, 1 (/1998), 21–36.
				MEZGER J., KIMMERLE S., ETZMUSS O.: Hierarchical Techniques in Collision Detection for Cloth Animation. Journal of WSCG 11, 2 (2003), 322–329.
		b. Robust treatment
			i. Still not perfect
				1) BRIDSON R., FEDKIW R. P., ANDERSON J.: Robust Treatment of Collisions, Contact, and Friction for Cloth Animation. In Proceedings of ACMSIGGRAPH ’02 (2002), ACM Press, pp. 594–603.
		c. Hardware
			i. GOVINDARAJU N., KNOTT D., JAIN N., KABUL I., TAMSTORF R., GAYLE R., LIN M., MANOCHA D.: Interactive collision detection between deformable models using chromatic decomposition. In Proceedings of ACMSIGGRAPH ’05 (2005),ACMPress.
			ii. THOMASZEWSKI B., BLOCHINGER W.: Physi- cally based simulation of cloth on distributed memory ar- chitectures. Parallel Computing 33 (2007), 377–390.
			iii. THOMASZEWSKI B., PABST S., BLOCHINGER W.: Exploiting parallelism in physically-based simula- tions on multi-core processor architectures. In Eurograph- ics Symposium on Parallel Graphics and Visualization (EGPGV ’07) (2007).
			
				
				
			
