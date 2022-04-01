<!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q 
#exit # scriptedIllustrator_markup_uk4uPhB663kVcygT0q 
# <html style="size: letter;"> <!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
#!/usr/bin/env bash

# Dependencies.
# May need 'ubiquitous_bash.sh" in "$PATH".
# GNU Octave, Qalculate - usually dependency of 'calculator' scripts
# recode - usually dependency of 'markup documentation' scripts
# wkhtmltopdf - may be necessary for accurate conversion from HTML to PDF

# NOTICE: README !
# 
# 
# 
# NOTICE: README !

# CAUTION: As a user, you should have been provided a virtual machine or cloud services to run this script - 'ubiquitous bash' provides functions to ease the use of either and both. An SELinux, AppArmor, unprivileged ChRoot, or similar context may be acceptable as well. Routinely modifying, sharing, and running code, may otherwise put both users and organizations at possibly unnecessary risk.


# Copyright and related rights only waived via CC0 if all specified conditions are met.
# *) EITHER, a single file directly output from 'scriptedIllustrator' (which is GPLv3 licensed), OR, not otherwise claimed under other any copyright license.
# *) Is a documentation script including this message which also predominantly creates or represents markup (eg. 'scriptedIllustrator.sh', 'scriptedIllustrator.html', 'scriptedIllustrator.mediawiki.txt').
# *) NOT part of a program to compress, embed, and assemble, functions and other code (waiver does NOT apply to 'tinyCompiler_scriptedIllustrator.sh' ).

# To the extent possible, related software (ie. 'tinyCompiler_scriptedIllustrator.sh' from 'scriptedIllustrator') remains otherwise copyrighted (ie. GPLv3 license).
# Specifically, please do not use 'scriptedIllustrator' code to distribute unpublished proprietary means of creating 'current_internal_CompressedFunctions' .
# Specifically, please do not misconstrue this copyright waiver to negate any copyright claimed when such a documentation script is part of another project or another copyright notice is present (ie. 'otherwise claimed').

# 'For the avoidance of doubt, any information that you choose to store within your own copy' ... 'remains yours' ... 'using' ... 'to publish content doesn't change whatever rights you may have to that content.'
# Although this project has no relation to TiddlyWiki, as stated above, vaguely similar copyright principles are expected to apply. - https://tiddlywiki.com/static/License.html

#__README_uk4uPhB663kVcygT0q_README__


_document_collect() {
# NOTICE: COLLECT

true




# NOTICE: COLLECT
}


# TODO: TODO: TODO: TODO: TODO: WIP !
_document_main() {
#a
#b
# NOTICE: DOCUMENT
#__HEADER_uk4uPhB663kVcygT0q_HEADER__
 '_' '_o' 'date' '--iso-8601'
 '_heading1' 'microFab'
if false; then true; # -->
<!-- # --><h1>microFab</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">Off-the-shelf microscope and pico projector UV ~365nm photolithography and 
metrology compact lab tool.

May affirm important expectations (<1000mJ/cm2 from light source for 
photolithography) and good practices (eg. water purity) for 
&#39;lithoDive&#39; "$photolithography_joules_cm2" . Also a useful compact 
tool for labs which may not be able to spare much floor space.

[Projector] -> [Adapter (optional)] -> Eyepiece -> (microscope) -> 
Objective -> Workpiece (wafer or webcam)

[Illumination -> Condenser -> Spatial Light Modulator -> Lens] -> [Macro 
Lens ~2x -> Diffuser -> Lens -> Cylinder -> Cylinder] -> Eyepiece -> 
(microscope) -> Objective -> Workpiece (wafer or webcam)

Webcam <- Cylinder (optional) <- Cylinder (optional) <- Eyepiece <- 
(microscope) <- Objective <- Workpiece (wafer or webcam)


Adapter parts are all optional. Flipping projector lens backward or 
otherwise adjusting projector focus may eliminate need for adapter. 
Diffuser and cylinder lens may simplfy uniformity and (astigmatic) focusing.
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Bill-Of-Materials'
if false; then true; # -->
<!-- # --><h1>Bill-Of-Materials</h1>
<!--
fi
 '_heading1' 'Projector'
if false; then true; # -->
<!-- # --><h1>Projector</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
>Brookstone 801143   ~$100
Pico DLP projectors seem like a nice BOM line item - cheap, compact, and 
ready to be reassembled with a new UV light source or used as a bare DLP 
chip on a flexible PCB with nearby HDMI controller.
Such a compact projector could be converted to a standard module that just 
fits on the eyepiece of a trinocular port, which human eyes and webcams 
have already standardized.
Not expecting any of the usual issues &#39;hacking&#39; DLP projectors to 
pass UV ~365nm from the mercury lamp. Should remain cheaply available too - 
the DLP chip and such they are made with is actually comparably cheap (IIRC 
~$20).
https://www.youtube.com/watch?v=ZtpHRiORFP8
https://www.youtube.com/watch?v=IExXIegZhsM

>E4500MKII   optional upgrade later
UV projectors already seem to exist, off-the-shelf. A nice upgrade path 
from a tiny pico projector if better quality optics or more pixels per 
exposure is really justified by ongoing production or months of delays from 
image quality (eg. contrast ratio, optics blurring, aberration) issues.
Minimum working distance is 25mm, it can&#39;t spread the light much more 
than that, so any &#39;macro lens&#39; ~25mm diameter or larger can 
recapture all the light.
https://www.ekbtechnologies.com/e-store/lightcrafter-e4500mkii-plus-365nm?c=
5cb86ca432c93

Heavier DLP projectors may include better quality and larger aperture 
optics. However, disabling color wheel and adding a UV pass hot mirror may 
require some &#39;hacking&#39; which may be uinque to each projector.
OpenBuilds linear rail, aluminum extrusion, crude kinematic/screw tilt 
plate, etc, could be built ad-hoc to mount projector to microscope.
https://en.wikipedia.org/wiki/Ultra-high-performance_lamp
https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=a
cer+dlp+projector&_sacat=0
https://packet39.com/blog/2016/03/19/how-to-remove-a-dlp-color-wheel-and-in-
my-case-also-destroy-the-projector/
https://www.edmundoptics.com/f/uv-hot-mirrors/13270/

Casio XJ-A140V   $200
I think I can hack these to use a different light source, no color wheel, 
etc. No guarantees, may still block too much UV ~365nm .
https://www.ebay.com/itm/275204929914?epid=84984702&hash=item40137df97a:g:hY
IAAOSwxM9iKpKc
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Illumination'
if false; then true; # -->
<!-- # --><h1>Illumination</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
>SST-10-UV-A130-F365-00   ~$10
LEDs UV 365nm 500mW/2mmDiameter apparently are available enough to rely on. 
Exposure of 0.1s/10umDiameter expected.
A module with a condenser (low quality short focal length lens) and 
diffuser may be necessary for uniformity and photodiode feedback power 
drift correction.
Low duty cycle may triple maximum power output.
Heatsink for LED required.
https://www.mouser.com/c/?q=365nm%20led
https://www.mouser.com/ProductDetail/Luminus-Devices/SST-10-UV-A130-F365-00?
qs=byeeYqUIh0Pj3UhvlMAaGA%3D%3D
https://www.mouser.com/ProductDetail/Luminus-Devices/SST-10-UV-A130-E365-00?
qs=nFovR%252B4R4UPzfxchETWTPw%3D%3D


LED in a 0805 package may be slightly higher intensity, at 120mW and 
<0.75mm expected diameter.
Smaller emitter area may be more difficult to align.
https://www.mouser.com/ProductDetail/Kingbright/ATS2012UV365?qs=%252BEew9%25
2B0nqrC2JRExRfahQQ%3D%3D
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Adapter - Macro Lens'
if false; then true; # -->
<!-- # --><h1>Adapter - Macro Lens</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
>ULANZI WL-1 ZV1   ~$50   ~2x   or any adequate &39;macro lens&#39;
&#39;Macro lens&#39;, as used by cameras, is usually a wide diameter lens, 
and reportedly can efficiently capture and refocus light from a projector 
to a small diameter for entrance into a microscope eyepiece or trinocular 
port. Any such lens with a diameter greater than the minimum unfocused 
image diameter directly in front of the projector should suffice.
More than one lens may be required to achive sufficiently short focal 
length to converge the divergent image.
https://amazon.com/Angle-ULANZI-Macro-Additional-Camera/dp/B08HQVZ2PC
https://www.youtube.com/watch?v=k3HEet5EXro
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Adapter - Diffuser'
if false; then true; # -->
<!-- # --><h1>Adapter - Diffuser</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
>#38-788   ~$25
https://www.edmundoptics.com/f/ground-glass-diffusers/12287/
	MAJOR - &#39;float glass&#39;
	MAJOR - &#39;Sandblasted on first surface&#39;
	MAJOR - &#39;Grit&#39; &#39;600&#39;
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Adapter - Lens'
if false; then true; # -->
<!-- # --><h1>Adapter - Lens</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
>Arducam M12 Lens Set   ~$100
M12 is compact and convenient.
As projection/camera imaging lenses, for converting a flat surface, a 
simpler lens may be inadequate.
https://www.amazon.com/Arducam-Raspberry-Arduino-Telephoto-Cleaning/dp/B07L9
2S9MT
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Adapter - Cylinder Lens'
if false; then true; # -->
<!-- # --><h1>Adapter - Cylinder Lens</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
https://www.39dollarglasses.com/
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Webcam'
if false; then true; # -->
<!-- # --><h1>Webcam</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
>MU1003   10MP USB 3.0 Color CMOS C-Mount Microscope Camera with Reduction 
Lens   ~$309.99
https://amscope.com/collections/microscope-parts-accessories?sort=price-asce
nding&pf_t_camera_connectivity=camera+connectivity%7CUSB+3.0
7.2fps @3584x2746
Sensor Size: 1/2.2inch (6.119mm(H) x 4.589mm(V), diagonal 7.649mm)
&#39;Featuring built-in C-mount compatibility and 23mm reduction lens 
adapter, our camera can be attached to any instrument with a C-mount or a 
23mm, a 30mm and a 30.5mm photo port.&#39;


>SC1003-CK   Swiftcam 10 Megapixel Camera for Microscopes   ~$309.99
Higher resolution may be important, but unusually, the benefits are only 
proportional to *linear* (ie. sqrt() ) resolution.
Compatibility with 25x eyepiece or similar is important - need to clearly 
see any projection image quality issues at center area.
https://amazon.com/Megapixel-Microscopes-Reduction-Calibration-Compatible/dp
/B07RNQC1WL
7.2fps at 3584x2746
CMOS sensor size: 1/2.3inch


>MD35   0.3MP USB 2.0 Color CMOS Digital Eyepiece Microscope Camera   ~$50
Cheap. Hack as an eyepiece projector adapter.
https://amscope.com/collections/microscope-parts-accessories?sort=price-asce
nding&pf_t_camera_connectivity=camera+connectivity%7CUSB+3.0&pf_t_camera_con
nectivity=camera+connectivity%7CUSB+2.0
&#39;23mm ocular or photo ports, but it can be adapted to fit 30mm or 
30.5mm ports using the included sleeves&#39;

>Logitech C270   ~$20
Bad for resolution. One of the very few USB cameras I have found stable 
with Linux/RasPi over many years.
https://www.thingiverse.com/thing:2055953
https://amazon.com/gp/product/B004FHO5Y6/
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Microscope'
if false; then true; # -->
<!-- # --><h1>Microscope</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
>T120-WM   $351.99
https://amscope.com/collections/compound-microscopes/products/t120-wm
https://amscope.com/collections/microscope-parts-accessories-microscope-obje
ctive-lens-microscope-achromatic-objective-lens/products/a60x-yx-v460
https://amscope.com/products/pa60x-v300
https://amscope.com/products/ep25x23-s


>RMH4T250X   $289.00
RMH4TL250X???
RXL4T???
Not sure what the &#39;L&#39; or other letters in &#39;Microscopes 
India&#39; model numbers signifies. Definitely do NOT want polarizer or 
anything else &#39;extra&#39; that could block UV 365nm or melt under 
intense concentrated light . Might be lowest risk to go with the least 
featureful microscope.
If any of the mechanical stages are better, that might be worthwhile, but 
feedback controlled stepper motors seems simple to build and too much to 
ask for from &#39;commercial-off-the-shelf&#39;.
https://www.ebay.com/sch/i.html?_dmd=2&_dkr=1&iconV2Request=true&_ssn=micros
copesind&store_name=microscopesindia&_oac=1
&#39;METAL RACK&#39; &#39;PINION&#39; &#39;NO PLASTIC GEAR&#39;
&#39;SEMI PLAN Achromatic&#39;
&#39;WF 10x&#39; &#39;WF 25x
https://www.ebay.com/itm/143405630452?hash=item2163a443f4:g:pDwAAOSwl9BWHUmj
https://www.ebay.com/itm/163897106947?hash=item2629076203:g:qhYAAMXQfFJRNJSV
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_' '_heading1' 'Introduction'
 '_' '_t' 'Precedents for usefulness, feasibility, etc?

Existing hardware, wetware, software adequacy? Scaling of hardware, wetware, or software needed?
'
 '_heading1' 'Conclusions'
if false; then true; # -->
<!-- # --><h1>Conclusions</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">*) Spare objectives should be kept for fine work only, in case objectives 
tend to get degraded.

*) Flourescence microscope may be better. Compound microscope should be 
adequate, cheaper, and will offer an opportunity to affirm if there are any 
issues at 365nm, and characterize such issues definitively.

*) Short exposure times may be strictly required for quality. Exposed 
photoresists, IIRC from a university tutorial referenced by 
&#39;lithoDive&#39;, reportedly must be developed within one hour at most. 
This strongly implies that a small amount of light activates a substance 
within the photoresists, which further sensitizes the photoresist to both 
heat and light.

*) Red or orange liquid could protect photoresist outside the current area 
under the imager. Such liquid could be removed and deposited completely due 
to surface tension, or if not, washed away by clear liquid.

*) If a device takes multiple days of scanning to fabricate, due to exposed 
photoresist degradation, completely fabricating entire layers in one scan 
may be impossible. Dividing layer into separate pieces to develop, 
etch/deposit, etc, separately, may be necessary.

*) LED. At least <365nm >0.01mW/10umDiameter . A 1mm 100mW LED would 
require ~0.1s/10umDiameter exposure time. Formula is 100000 / (((1 * 
centimeter)^2) / ((10 * micrometer)^2)) = 0.1 . The &#39;100000&#39; is the 
&#39;photolithography_seconds_cm2= 100000&#39; &#39;Photolithography Joules 
(Watt-Seconds) Constrained&#39; from &#39;lithoDive&#39;.


*) Focus will be by projected image only - mirror polish surface will look 
featureless, blank. Without projection, the image would look the same both 
in and out of focus. No optical microscope see anything in a mirror. Some 
tricks will make this easier if necessary, such as astigmatic focusing, 
using a more interesting sample, or using a webcam CCD as a sample and 
sensor.

*) Microscope objective at 60x will be most convenient to have, best 
non-immersion resolution. Shortening projector resolution to nearly that of 
eyepiece, rather than projecting directly into microscope, may improve 
resolution substantially.

*) Cannot rely on expecting to get away with 445nm, or 405nm. Must be 
prepared for <365nm, DLP projector mercury-vapor 
&#39;Ultra-high-performance_lamp&#39; equivalent. Not all projectors have 
this.

*) Vacuum chuck may help with vibration during long or high-resolution 
(<3um) imaging. Depth-of-field (focus depth) may be nanometers, wafers are 
thin and lightweight.


*) Good mechanical stages are at least stepper motor driven with optical 
feedback to correct backlash. If such custom hardware is necessary, 
development or assembly time will be necessary. &#39;Slabs&#39; and the 
gantry from &#39;lithoDive&#39; are the appropriate technology to develop 
in that case. Should be simpler to add stepper motor wheels to a flat slab 
than to adapt stepper motors to existing stages.

*) Tilt tolerance between projector/microscope/workpiece should be ~1deg 
for the <100um FOV usual for microscopes, unlike the large FOV of larger 
photolithography machines and possibly &#39;lithoDive&#39;. Tilt correction 
should not be necessary.
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Astigmatic Focusing'
if false; then true; # -->
<!-- # --><h1>Astigmatic Focusing</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">Astigmatic focusing will place a purely, slightly, cylindrical lens in 
front of a webcam, essentially an &#39;eyeglasses prescription&#39; to 
deliberately add slight astigmatism. As a cylindrical lens will focus to a 
line at a plane close than the spherical lens focal plane. Thus, when 
projecting a dot, if too close, a large oval will appear. If too far, both 
the spehrical and cylinder lens will be out of focus, and a large oval *in 
the opposite direction* will appear.

Same technique can be used to focus the projector independently. Projector 
can be given a diagonal lens, while the camera uses a horizontal/vertical 
lens, to visualize the focus of both projector and webcam simultaneously 
and separately.


Two cylinder lenses may be rotated to exactly nullify the cylinder focusing 
without changing the rate of refraction in the light path. During focusing, 
both cylindrical lenses are present. When done, one of these is replaced 
with a divergent lens (essentially an &#39;eyeglasses prescription&#39; to 
correct the introduced astigmatism).
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'errata'
if false; then true; # -->
<!-- # --><h1>errata</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">*) Focus - not possible without projection. A mirror finish surface has no 
visible features for any optical microscope to focus, and will always look 
like just a blank color.

*) Just pointing a projector at a microscope eyepiece reportedly actually 
works... just like any lens refocusing projector output a small image on a 
wall.


*) Photoresists seem to nonlinearly sensitize and degrade if not developed 
quickly after brief exposure, imposing a requirement for intense light, 
fast exposure, high contrast ratio, uniformity, etc. Slow exposures or 
overexposure apparently may be *very bad* for quality.
 *) Also that is very consistent with the many issues I had with 
high-resolution 6mil PCB fab. Had I known, I might have tried deliberate 
underexposure.


*) DLP pico projectors all seem to have small electronics, less filters, 
few screws, and put the DLP on a flex PCB, like a better and cheaper 
evaluation kit.
 *) DLP pico projector should not require adapter. Should be much more 
straightforward to modify for ultra short &#39;throw&#39; - less material 
to remove, smaller required projection lens aperture, bare DLP if 
necessary, etc.
 *) Having already replaced the light source with a uniformly diffused 
365nm UV LED obviates conversion to diffused rear-projection also.

*) Most DLP projectors usually have a 365nm lamp, but almost completely 
filter out the UV, with apparently severe impact on quality, unformity, 
etc. Hacking and improving these may not be easiest.


*) Cheap trinocular compound microscope is expected to work.
*) Flourescence microscope may be a little better but NOT necessary.


*) Impurities seem irrelevant. All materials reportedly used seem commonly 
available. Scanning microscope could detect and overwrite/rewrite/etc 
around dust particles or other defects.
*) Photoresist is shown *red* colored for mercury vapor.
 *) https://youtu.be/Nxz_ENnmgtI?t=200

*) Expect ~10um FOV (yes, 10 microns).



*) Differential Interference Contrast may use a diffuse &#39;interference 
plane&#39; which may melt under projection if plastic, paper, etc.

*) Imaging quality is required for all optics not a few orders of magnitude 
out of the focal plane.

*) Light focus at a point prior to microscope lens may be necessary, unlike 
presentation projectors.

*) Incident Brightfield is through-objective illumination (or presumably, 
projection), required.


*) Reported use of inkjet transparencies with flourescence microscopes, 
suggests 0.6um (600nm) with contrast ratio as low as 10:1 is routinely 
achievable when maximum resolution was obviously not prioritized. Still, 
resist over/under exposure may be orders of magnitude more critical at 
lower resolutions or if other aspects are underperforming (eg. poor focus, 
projector tilt, inadequately calibrated vignetting, etc).






*) Reportedly, a photoresist can be inspected and redone. If that can 
happen without damaging nanometer thick layers, or if at least deep layers 
can be protected, the selective, maskless, small-area, automatic design of 
&#39;lithoDive&#39; would be a perfect fit for unusually extensive 
*multiple patterning*.

*) Immersion lithography is not prohibitive. Photoresist should protect 
wafer. Computer feedback and repeated exposures should be able to overwrite 
defects due to immersion liquid particles, if not optically detect 
particles and replace immersion liquid when particles are present.
 *) Slabs (ie. &#39;lithoDive&#39;) must already have spill reservoirs and 
dump ports for other &#39;wet&#39; uses.


*) Microscope - tube lens, beamsplitter, prisms, mirrors, trinocular - 
these seem rather valuable these days.








*) Salvage an &#39;Ultra-high-performance_lamp&#39; DLP projector from a 
resin 3D printer.

*) Fake RGB Arduino. Records an RGB sequence from photodiodes during a 
button press then plays back that RGB sequence to LEDs (universal DLP 
projector color wheel hack).



*) Get an intense UV light source for DIY projector, photomask, or to add 
to Casio XJ-A140V projector.

 *) Figure out electrical power for a separate ultra-high-performance lamp.
https://en.wikipedia.org/wiki/Ultra-high-performance_lamp

 *) Nitrogen laser, 337nm. Bulky, and mirror bounces would be necessary, 
may be too short wavelength for most DLP. Ok for &#39;lithoDive&#39;, or a 
DLP pico projector. NOT convenient for already bulky projectors or 
constrained light paths.

 *) DIY, YouTube, etc, sourced nitrogen laser. Maybe not worth the effort.
https://www.youtube.com/watch?v=d19dM8ZB3Qs

 *) Laser, 375nm. Seems rare and barely affordable.
https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=3
75nm+laser&_sacat=0

 *) Laser 355nm. Seems rare and a poor investment.
https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=3
55nm+laser&_sacat=0

 *) LED. At least <365nm >0.01mW/10umDiameter . A 1mm 100mW LED would 
require ~0.1s/10umDiameter exposure time. Formula is 100000 / (((1 * 
centimeter)^2) / ((10 * micrometer)^2)) = 0.1 . The &#39;100000&#39; is the 
&#39;photolithography_seconds_cm2= 100000&#39; &#39;Photolithography Joules 
(Watt-Seconds) Constrained&#39; from &#39;lithoDive&#39;.
https://www.mouser.com/c/?q=365nm%20led
	Some LEDs have could have ~0.5W output at 2mm at 365nm diameter.

  *) LED may require defocusing and/or dedicated diffuser with focusing 
lenses to ensure uniformity.


*) Off the shelf hard-UV projector. These apparently do exist, and if the 
LEDs chosen were high-intensity, could be near-optimal.
https://www.ekbtechnologies.com/e-store/3d-printer-platforms
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_heading1' 'Safety'
if false; then true; # -->
<!-- # --><h1>Safety</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
Do NOT observe microscope output directly without orders of magnitude of 
well calculated redundant attenuation (eg. multiple layers of scratch-free 
sunglasses) at the eyepiece. Obviously, projecting ~100mW, or tens of 
watts, through a microscope, will be blindingly bright. If you cannot 
anticipate and take all reasonable precautions, do not attempt anything 
described here. Your accident is your accident.
<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_page' ' '
if false; then true; # -->
<!-- # --><div style="page-break-before: always;margin: 0;padding: 0; border-width: 0px;"> </div>
<!--
fi
 '_heading1' 'REFERENCE'
if false; then true; # -->
<!-- # --><h1>REFERENCE</h1>
<!--
fi
_t '
scriptedIllustrator_markup_uk4uPhB663kVcygT0q --><!-- # --><pre style="margin-top: 0px;margin-bottom: 0px;white-space: pre-wrap;">
https://www.quora.com/How-does-a-CD-laser-focus
https://www.physics.udel.edu/~watson/scen103/cd-astig.html

https://www.39dollarglasses.com/
	Both convergent and divergent cylinder lenses should be obtainable 
as an eyeglass prescription.

https://www.youtube.com/watch?v=Nxz_ENnmgtI
	&#39;macro lens adapters&#39; &#39;using two of them&#39; &#39;beam 
that converges somewhere in the microscope body&#39; &#39;simulation can be 
useful here but you don&#39;t really know the parameters of cheap 
lenses&#39;
	&#39;first prototypes were a lot sketchier and just involved 
shooting an unmodified projector right into the camera or eyepiece port of 
a microscope and that gets you pretty decent results actually&#39;


http://www.ijaist.com/wp-content/uploads/2018/08/QUARTZCRYSTALFORTHICKNESSME
ASUREMENT-1.pdf
	Quartz crystal under same conditions as wafer can measure oxide 
growth by slight frequency shift.









https://www.ti.com/dlp-chip/overview.html
https://www.ti.com/tool/DLPDLCR2000EVM#buy
https://www.ti.com/dlp-chip/advanced-light-control/ultraviolet/products.html
https://www.ti.com/product/DLP7000UV



https://en.wikipedia.org/wiki/Ultra-high-performance_lamp

https://www.mouser.com/c/?q=365nm%20led


https://www.mouser.com/ProductDetail/LED-Engin/LZ1-00UV0R-0000?qs=P1JMDcb91o
4eQ1bt2b01Zg%3D%3D
https://www.mouser.com/datasheet/2/228/LED_Engin_Datasheet_LuxiGen_LZ1-00UV0
R_rev2.0_2020-1889174.pdf
	&#39;flux density&#39;

https://www.mouser.com/datasheet/2/678/AUV3_Sxx2_0xx0K_DS100-1923831.pdf
	&#39;Radiant Flux Bin&#39; &#39;Max&#39; &#39;910&#39; &#39;mW&#39;




https://www.edmundoptics.com/c/optical-diffusers/731/
https://www.edmundoptics.com/f/ground-glass-diffusers/12287/
	MAJOR - &#39;float glass&#39;
	MAJOR - &#39;Sandblasted on first surface&#39;



https://www.ebay.com/sch/i.html?_dmd=2&_dkr=1&iconV2Request=true&_ssn=micros
copesind&store_name=microscopesindia&_oac=1
https://www.ebay.com/sch/185278/i.html?_dmd=2&_dkr=1&iconV2Request=true&_ssn
=microscopesind&store_name=microscopesindia&_oac=1
	&#39;Microscopes India&#39;

https://amscope.com/collections/compound-microscopes?gclid=Cj0KCQjw3IqSBhCoA
RIsAMBkTb3wiV0H5v8I39RqAGZyU6SwfOVa_rYzjrXcOyErAgd6BhCLt-iHhrEaAgezEALw_wcB&
gclsrc=aw.ds&sort=price-ascending&pf_t_head_style=head+style%7CMicroscopes-T
rinocular

https://amscope.com/collections/microscope-parts-accessories-microscope-obje
ctive-lens-microscope-achromatic-objective-lens/products/a60x-yx-v460
	&#39;60x&#39;
		MAJOR - Worth getting.


https://www.edmundoptics.com/f/international-standard-microscope-objectives/
11958/
	&#39;60x&#39;

https://www.edmundoptics.com/f/nikon-achromatic-finite-conjugate-objectives/
13510/
	&#39;60x&#39;






https://amscope.com/collections/compound-microscopes/products/t120-wm
	&#39;Eyepieces: 10X&#39;
	&#39;40X(S), 100X(S, Oil)&#39;



https://www.mouser.com/c/?q=lightcrafter&sort=pricing


https://www.mouser.com/ProductDetail/Texas-Instruments/DLPDLCR230NPEVM?qs=zW
32dvEIR3tiMHYZswsS3g%3D%3D
	&#39;New Product&#39;
	&#39;Factory Lead-Time&#39; &#39;3 Weeks&#39;
	&#39;$397.66&#39;

https://www.ti.com/lit/ug/dlpu103a/dlpu103a.pdf?ts=1648526971271
	Seems to connect only to RasPi.

https://www.ekbtechnologies.com/e-store/e4750lc-uv-405nm-full-hd-1?c=5cb86ca
432c93
	&#39;385nm&#39; &#39;1.5W&#39;



https://www.edmundoptics.com/c/microscopy/625/#
	&#39;Infinity Corrected Objectives&#39;
	&#39;Finite Conjugate Objectives&#39;
	&#39;Reflective Objectives&#39;
	&#39;TECHSPEC® Objectives&#39;
	&#39;Eyepieces&#39;

https://www.edmundoptics.com/c/reflective-objectives/709/#
https://www.edmundoptics.com/f/high-performance-reflx-objectives/13550/
https://www.edmundoptics.com/f/reflx-objectives/13142/
	&#39;DUV Enhanced Aluminum (150-11000nm)&#39; &#39;0.33&#39; (NA)

https://www.edmundoptics.com/c/infinity-corrected-objectives/629/#
	&#39;Fluorescence&#39;

https://www.edmundoptics.com/c/finite-conjugate-objectives/708/#
	&#39;Commercial Grade Standard Microscope Objectives&#39;


https://www.edmundoptics.com/f/accessory-tube-lenses/12619/
	&#39;Mitutoyo Tube Lenses&#39;



https://www.youtube.com/watch?v=Nxz_ENnmgtI
	Seems to use built-in *mercury vapor* light. So we cannot expect to 
get away with 445nm. After all, this should be a several watt source, so 
efficiency is less of a concern.
	Seems the &#39;~800nm line width&#39; is sharp enough to get to 
&#39;~400nm line width&#39; or better if FOV were traded for resolution.

https://youtu.be/97ARLiTHjX0?t=664
	&#39;UV blocker&#39;
		MAJOR - Could significantly affect the lateral resolution 
for 2d photolithography at high resolution (or otherwise relatively high 
ratios of photoresist thickness and feature size) as well. This is the sort 
of unexpected issue which necessitates test fixtures (eg. CCD cameras) to 
measure performance of the optics independent of actually doing 
photolithography.







https://en.wikipedia.org/wiki/Optical_microscope
	&#39;Polarised light may be used to determine crystal orientation 
of metallic objects.&#39;


https://www.leica-microsystems.com/science-lab/metallography-an-introduction
/
	&#39;Brightfield&#39; &#39;Darkfield&#39; &#39;Differential 
Interference Contrast (DIC)&#39;


https://www.researchgate.net/figure/Figure-A2-Beam-path-in-differential-inte
rference-microscopy-The-first-Nomarski-prism_fig63_280664165
	Apparently there should be an &#39;interference plane&#39;, 
presumably where an image is projected onto a diffuse surface, not shown by 
leica.

https://openflexure.org/projects/microscope/



https://arxiv.org/pdf/1806.08718.pdf
 &#39;Microscope Projection Photolithography Based on Ultraviolet 
Light-emitting Diodes&#39;
	&#39;final pattern width of the single slit was 17 um, which was 
about half that of the one in the photomask&#39;
	&#39;-number of the 4X objective lens is 5.0 since its numerical 
aperture was 0.10&#39;
	&#39;theoretical resolution is 2.0 μm, assuming that the 
wavelength is 0.40 μm&#39;
	&#39;actual resolution limit is about 4 μm, which is close to the 
minimum line width measured in our experiment&#39;
	Looks like a through-beam trinocular microscope was used. This 
could not have been a metallurgical microscope, and the necessity of adding 
a UV light source (ie. built-in the non-incident brightfield illumination 
could not have been) also rules out this having been a metallurgical 
microscope. Projecting simple photomasks instead of computer projectors is 
also an interesting experiment.

https://gmwgroup.harvard.edu/files/gmwgroup/files/757.pdf
 &#39;Microscope Projection Photolithography for Rapid Prototyping of 
Masters with Micron-Scale Features for Use in Soft Lithography&#39;
	&#39;transparency film masks&#39; &#39;routinely&#39; &#39;down to 
0.6 μm&#39;
	&#39;100× objective&#39; &#39;limited to a circle with a radius of 
∼100 μm by uneven light intensities at the edges of the image and 
optical distortions of the features in the mask near the edges&#39;
	Apparently modified a flourescence microscope.





https://www.instructables.com/RooBee-One-SLA-DLP-Aluminum-Frame-3D-Printer/
	&#39;Acer X113P&#39;
		Does not seem widely available. Suitable projectors as 
consumer products seem trendy, likely displaced by newer projector hardware 
and cheapening of many other display technologies.






https://www.youtube.com/watch?v=waBjGxsGSg8
	&#39;focus mechanism is electronically coupled to the camera so it 
only works when the camera is turned on&#39;



https://www.youtube.com/watch?v=KjdJwE9pkUo
	&#39;This rig gave me the freedom to adjust tilt, height, rotation 
precisely.&#39;
		Resolution seems rather significantly degraded and 
distorted. Although it is possible to workaround by trading FOV for 
resolution.

https://www.amazon.com/dp/B0047YRKK8/














<!-- # --></pre><!-- scriptedIllustrator_markup_uk4uPhB663kVcygT0q
'
 '_' '_page' ' '
 '_' '_heading1' 'Example: Pessimistic Estimate - Something - Description'
 '_' '_t' '$variable1 == Presume something .

$variable2 == Presume something .

$variable3 == Negligible .

'
 '_' '_e_' 'variable1=1'
 '_' '_e_' 'variable2=$(_clc " 1 + 1 " )'
 '_' '_e_' 'variable3=0'
 '_' '_e_' '_solve' '"( \"variableX\" == "$variable1" * "$variable2" + "$variable3" , \"variableX\" )"'
 '_' '_e_' '_solve' '"( \"variableZ\" == "$variable1" * "$variable2" + "$variable3" , \"variableZ\" )"'
 '_' '_o' '_safeEcho_newline' 'units. Some number of other units is approximately some number of those units.'
 '_' '_t' 'For whatever reason these results are an estimate of the most challenging part of the part of the problem modeled by this equation. Other related stuff may be change things a bit but not by so many orders of magnitude as to (in)validate feasibility.'
 '_' '_heading1' 'Example: Pessimistic Estimate - Something - Description'
 '_' '_t' '$variable1 == Presume something .

$variable2 == Presume something .

$variable3 == Negligible .

'
 '_' '_e_' 'variable1=1'
 '_' '_e_' 'variable2=$(_clc " 1 + 1 " )'
 '_' '_e_' 'variable3=0'
 '_' '_e_' '_solve' '"( \"variableX\" == "$variable1" * "$variable2" + "$variable3" , \"variableX\" )"'
 '_' '_e_' '_solve' '"( \"variableZ\" == "$variable1" * "$variable2" + "$variable3" , \"variableZ\" )"'
 '_' '_o' '_safeEcho_newline' 'units. Some number of other units is approximately some number of those units.'
 '_' '_t' 'For whatever reason these results are an estimate of the most challenging part of the part of the problem modeled by this equation. Other related stuff may be change things a bit but not by so many orders of magnitude as to (in)validate feasibility.'



#__FOOTER_uk4uPhB663kVcygT0q_FOOTER__
# NOTICE: DOCUMENT
#y
#z
echo -e '\n\n'
}



# NOTICE: Overrides - new functions .


# NOTICE: Overrides - new functions .


#####Functions. Some may be from 'ubiquitous bash' .
#_compressedFunctions_uk4uPhB663kVcygT0q_compressedFunctions_uk4uPhB663kVcygT0q_compressedFunctions_uk4uPhB663kVcygT0q_compressedFunctions
current_internal_CompressedFunctions_bytes="12375"
current_internal_CompressedFunctions_cksum="3023785929"
current_internal_CompressedFunctions="
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"
! echo "$current_internal_CompressedFunctions" | base64 -d | xz -d > /dev/null && exit 1
source <( echo "$current_internal_CompressedFunctions" | base64 -d | xz -d )
unset current_internal_CompressedFunctions ; unset current_internal_CompressedFunctions_cksum ; unset current_internal_CompressedFunctions_bytes
# https://github.com/mirage335/scriptedIllustrator
#_compressedFunctions_uk4uPhB663kVcygT0q_compressedFunctions_uk4uPhB663kVcygT0q_compressedFunctions_uk4uPhB663kVcygT0q_compressedFunctions
! _tiny_criticalDep && exit 1

# Special Global Variables
_tiny_set_strings


#####Import ( 'ubiquitous bash' ) .
# WARNING: Do NOT invoke complicated 'ubiquitous bash' functions directly (ie. call "ubiquitous_bash.sh" as a binary from PATH instead) .
# WARNING: If '--call' parameter is changed, 'trap' conflict may occur in some functions (ie. ( '_test_default' ) .
# Keeps "$scriptAbsoluteLocation" pointing to this script file (not 'ubiquitous_bash.sh' ), intentionally.
# Import of 'ubiquitous_bash.sh' intended ONLY to provide most recent 'message' and similar functions.
#_messagePlain_probe() { return; }
! type -p "ubiquitous_bash.sh" > /dev/null 2>&1 && exit 1
[[ "$ubiquitousBashID" != "uk4uPhB663kVcygT0q" ]] && exit 1
current_script_path=$(type -p "ubiquitous_bash.sh")
[[ ! -e "$current_script_path" ]] && exit 1
! ls -l "$current_script_path" 2>/dev/null | grep 'ubiquitous_bash.sh$' > /dev/null 2>&1 && exit 1
export importScriptLocation=$(_getScriptAbsoluteLocation)
export importScriptFolder=$(_getScriptAbsoluteFolder)
. "$current_script_path" --call
unset current_script_path
#_messagePlain_probe "$scriptAbsoluteLocation"
#exit 0



#a
#b
#c
#__HEADER-scriptCode_uk4uPhB663kVcygT0q_HEADER-scriptCode__
#1
#2
#3



#8
#9
#0
#__FOOTER-scriptCode_uk4uPhB663kVcygT0q_FOOTER-scriptCode__
#x
#y
#z

# NOTICE: Overrides ( 'ops.sh' equivalent ).

_default_procedure() {
	! _safePath "$scriptLib" && echo 'fail: _safePath' && return 1
	
	# Consolidating self, a 'draftedDocument' (usually an Xournal sketch), two separate documents (usually also created by a scriptedIllustrator script).
	#pdfseparate "$scriptLib"/draftedDocument.pdf -f 1 -l 2 "$scriptLib"/draftedDocument-%d.pdf
	#pdfunite "$scriptLib"/"$1".pdf "$scriptLib"/draftedDocument-*.pdf "$scriptAbsoluteFolder"/z01-templateArticle.pdf "$scriptAbsoluteFolder"/z02-templateArticle.pdf "$scriptAbsoluteFolder"/"$1".pdf
	#rm -f "$scriptLib"/'draftedDocument-'*'.pdf' > /dev/null 2>&1
	
	# Copy self, as is.
	cp "$scriptLib"/"$1".pdf "$scriptAbsoluteFolder"/"$1".pdf
	
	
	
	
	
	
	rm -f "$scriptLib"/"$1".pdf > /dev/null 2>&1
}
_default() {
	mkdir -p "$scriptLib"
	
	! type -p qalculate > /dev/null 2>&1 && exit 1
	_solve() {
		_qalculate_solve "$@"
	}
	_clc() {
		_qalculate "$@"
	}
	
	local current_deleteScriptLocal
	current_deleteScriptLocal="false"
	[[ ! -e "$scriptLocal" ]] && current_deleteScriptLocal="true"
	
	"$scriptAbsoluteLocation" DOCUMENT > "$scriptAbsoluteLocation".out.txt
	
	#_scribble_markdown "$@"
	#_scribble_html "$@"
	_scribble_pdf "$@"
	
	local currentScriptBasename
	currentScriptBasename=$(basename "$scriptAbsoluteLocation" | sed 's/\.[^.]*$//')
	#_scribble_html "$@"
	#[[ -e "$scriptAbsoluteFolder"/"$currentScriptBasename".html ]] && "$scriptAbsoluteFolder"/"$currentScriptBasename".html _test
	rm -f "$scriptAbsoluteFolder"/"$currentScriptBasename".html > /dev/null 2>&1
	
	
	mv -f "$scriptAbsoluteFolder"/"$currentScriptBasename".pdf "$scriptLib"/"$currentScriptBasename".pdf
	_default_procedure "$currentScriptBasename"
	
	mv -f "$scriptAbsoluteFolder"/"$currentScriptBasename".pdf "$scriptAbsoluteFolder"/"$currentScriptBasename".sh.pdf
	
	
	[[ "$current_deleteScriptLocal" == "true" ]] && [[ -e "$scriptLocal" ]]  && rmdir "$scriptLocal"
	
	
	_scribble_markdown "$@"
	mv "$scriptAbsoluteFolder"/"$currentScriptBasename".md "$scriptAbsoluteFolder"/README.md
	#sleep 3
}

# NOTICE: Overrides ( 'ops.sh' equivalent ).


_test() {
	"$scriptAbsoluteLocation" _test_default "$@"
}

if ! [[ "$1" == '_'* ]] && [[ "$1" == 'DOCUMENT' ]]
then
	_document_collect
	_document_main
fi

! [[ "$1" == '_'* ]] && [[ "$1" == 'DOCUMENT' ]] && exit 0
if [[ "$1" == '_'* ]]
then
	"$@"
	exit "$?"
fi



_default "$@"






exit 0
# Append base64 encoded attachment file here.
__ATTACHMENT_uk4uPhB663kVcygT0q_ATTACHMENT__


filename.html # scriptedIllustrator_markup_uk4uPhB663kVcygT0q --> </html>
