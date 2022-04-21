# openfusioncell
this is a repository for work relating to a high pressure anvil cell, containing a fusion fuel, particularly deteurated ice 7 (pressure frozen D2O).  

If we consider the lawson criterion:
https://en.wikipedia.org/wiki/Lawson_criterion

we find that a simple triple product of number density 'd', fuel ion temperature 'T' and confinement time 't' is generally used as the most critical figure of merit for determining if a given fusion system can attain ignition, what 'Q', fusion energy gain multiple, it will be limited to and at what temperature the maximum of these conditions should occur. 
There is still debate as to whether the lawson criterion fully encapsulates all forms of fusion reactor, and there is reason to believe it is increasingly unreliable for describing the behavior of systems beyond conventional warm plasmas of modern tokamak, ICF, pinch fusion and other gas phase reactors. 

All modern fusion concepts, with the notable exception of lattice fusion:
https://www1.grc.nasa.gov/space/science/lattice-confinement-fusion/

operate in a relatively low number density gas state. If they do attain higher number densities, it is only by inertial aceleration in electrostatic or magentic fields, both of which are known to be highly inefficient at attaining large number densities compared to conventional mechanical adiabatic processes.

Generally, the maximum attainable number densty in modern gas-plasma reactors is limited to 10^20 fuel ions per cubic centimeter. This represents an enormous limitation, as such a density only corresponds to about 1-2 atmospheres of plasma pressure. All known instances of fusion in the wider universe occur at far higher pressures. Of course, modern fusion concepts attempt to make up the difference with extreme temperatures up to 200E6 kelvin. This of course, thanks to the T^4 dependence of radiative emission with temperature, results in enormous energy losses through syncrotron radiation and other mechanisms, as well as demanding massive heating powers, huge confinement magnets cooled to cryogenic temperatures and a wide variety of other extremely heavy and expensive trappings. 

By contrast, the number density of fuel ions in ordinary water at room temperature and room pressure is 1E23 ions per cubic centimeter, already far higher than any conventional plasma reactor could hope to attain with even the biggest and most powerful confinement fields. Further, temperatures comparable and occasionally in excess of those generated in the most powerful gas plasma reactors to date have been demonstrably attained in small scale zeta pinch fusion(essentially neon signs), and even in common lightning strikes when their neutron and gamma ray spectrum has been measured. Additionally, your household smoke detector (if it is an ionization type device, containing an americium source) continuously emits alpha particles and neutrons at temperatures far in excess of 200E6 K (or 200 KeV) attainable in conventional reactors. Some of the alpha emissiosn of such ionization sources have been clocked at 5 MeV, corresponding to an ion temperature of 5E10 K! 

This all means simply, that conventioanl fusion approaches are probably not practical for the individual to realize as a home energy source and there are far better directions in which to look, as an individual, for powering ones home from hot nuclear fusion if one is so inclined. 

Here in the openfusioncell project, I propose a not so new, but I believe, fairly obvious, direction for the enterprising individual looking to harness the power of the nucleus at home. 

The concept is quite simple and should require no more than a few hundred dollars in parts and materials along with some time and elbow grease. 

We begin with an anvil cell similar to that described here :
https://en.wikipedia.org/wiki/Diamond_anvil_cell

instead of the expensive, electrically insulating and relatively troublesome to obtain diamonds, we substitute tungsten carbide or silicon carbide anvils into the cell. 

We then fill the gasket and lower half of the anvil cell, with a small amount ~0.5-1 cubic millimeter of deteurium oxide (D20) also known as heavy water. This can be purchased readily from places like bean town chemical and can be read about on wikipedia.
https://www.beantownchem.com/item/215835-50G
https://en.wikipedia.org/wiki/Heavy_water

Diamonds are the "diamond standard" for pressure cells in that their incredible hardness (and high bulk modulus) allows them to attain pressures under good conditions of 350-1000 GPa. In our case, the much cheaper silicon or tungsten carbide will still allow us to attain pressures < = 100 GPa without much trouble relatively speaking, and at several orders of magnitude lower cost. Further, the silicon carbide and tungsten carbide, being generally more electrically conductive than diamond, and better gamma ray and neutron absorbers / reflectors for the probable emissions of our chosen fuel makes them ideal for our application, as they allow easy electric field multiplication and current injection into the D2O pressure ice, once formed, and should enhance overall confinement of fusion byproducts. 

Before we get all excited, there is one further step that must be taken. The pressure in our anvil cell needs to be between 5 and 50 GPa to form stable Ice VII, a dense, ionic semiconductor ice, made of a pure oxygen lattice, in which the hydrogen (in this case Deteurium) atoms are free to move and flow, effectively solvated in a fermi sea of semi degenerate electrons, this, as in lattice fusion provides a screening charge on the order of the charge of the electron, which greatly reduces the overall couloumb barrier (like charge repulsion) that two possitive solvated deuteurium nuclei will experience in the electron sea. This pressure is far from the pressure at the center of the earth or in the core of the sun, however, and thus we will need some way of generating very high transient temperatures to get us the rest of the way to fusion conditions. One of the most familiar ways of attaining high transient temperatures and even neutron production,
https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.111.115003
is through dielectric barrier breakdown discharge plasmas. Essentially, when a sufficiently large voltage gradient builds up across a dielectric or semiconductor, such as our Ice VII, a discharge results from the sudden release of the stored charge on one side of the barrier to the other, which brings with it a corresponding enromous electric field, and magnetic field from the large instantaneous flow of current as established centuries ago by faraday's law of induction. This same process was historically harnessed to produce the earliest fusion devices known as Zeta-pinch configurations:
https://en.wikipedia.org/wiki/Z-pinch

This approach was generally abandoned due to the movement of funding to other methods such as the tokamak, but it did show promise as a simple, low cost neutron source despite the troubles with managing a gas phase plasma. In fact, in the modern day, the highest net gain record for net fusion fusion energy and highest plasma temperature has been set by a Z-pinch dense plasma focus configuration device by lawrenceville fusion labs:
https://lppfusion.com/

What all this means, is that, once we have confined and pressurizd our sample of D2O in our anvil cell, we can use the same pointiness of the anvils that provides the large pressure multiplication, to provide electric field enhancement http://www.lon-capa.org/~mmp/kap18/RR455.htm and optimal conditons for dielectric barrier breakdown discharges (and their associated extreme temperatures (50-200E6 K and magnetic pressures of some TPa) inside our confined high pressure sample of D2O ice VII.

the density of D2O at our confinement pressure, conservatively, 10 GPa, will be ~1.9 g/cc which corresponds to number density of 1.9E23 ions per cubic centimeter. given the the easily attainable temperature in our system of 50E6 K (or 50KeV electric field gradient in the cell). A reasonable arc breakdown lifetime given the properties of Ice VII, https://www.nature.com/articles/srep05778
is probably 1-10 ms. Conservatively 1 ms. 

If we apply our simple lawson criterion triple product dumbly to these values, 
1.9E23 ion/cc * 50E6 Kelvin * 0.001 seconds = 9.5e+27 K*s/m^3
as compared to the highest performing tokamak to date attaining 1.53e+21 K*s/m^3. 
That is 6 order of magnitude improvement, *simply by increasing the pressure and working in the solid state using commonly available and easy to purchase parts and materials*.

this is before we consider any probable enhancement by the highly reflecting cofninement conditions, the increased number densitie's effect on collision probabilities, and the beneficial lattice confinement like screening effect of the electron sea in Ice 7, or the probable large increases in deteuron density likely to occur in the the lattice during a breakdown event, since the magnetic confinement of the charge carriers in the breakdown (primarily the deteurons in Ice VII) can produce transient pressures far in excess of the static pressure in the cell. 

This entire package could readily be built into a device about the size of a softball.

Why has this not been tried yet? Even if the dielectric barrier breakdown is insufficient, the fuel could be seeded with americium to provide hot neutrons which, according the lattice fusion research at NASA Glenn, are far more efficient initiators of fusion reactions in a solid lattice than any charged particles.

Here in the openfusioncell project, we intend to give it a shot. 



