# Battery

Chemical reactions inside a battery occur more
slowly at low temperatures. 
Consequently, a cold
battery cannot deliver as much current as a warm
battery. For this reason, in winter weather, a car
battery is less able to deliver high current. At the
same time, because engine oil becomes more
viscous as the temperature falls, the starter motor will demand more current to turn the engine.
This combination of factors explains the tendency of car batteries to fail on cold winter mornings.

## Sulfurization
When a lead-acid battery is partially or completely discharged and is allowed to remain in
that state, sulfur tends to build up on its metal
plates. The sulfur gradually tends to harden,
forming a barrier against the electrochemical reactions that are necessary to recharge the battery. For this reason, lead-acid batteries should
not be allowed to sit for long periods in a discharged condition. Anecdotal evidence suggests that even a very small trickle-charging current can prevent sulfurization, which is why some
people recommend attaching a small solar panel
to a battery that is seldom used for example,
on a sail boat, where the sole function of the battery is to start an auxiliary engine when there is
insufficient wind.

## Reverse Charging

Reverse charging can occur when a battery becomes completely discharged while it is wired
(correctly) in series with other batteries that are
still delivering current. 
In the upper section of the
schematic at Figure 2-16 two healthy 6V batteries, in series, are powering a resistive load. 
The
battery on the left applies a potential of 6 volts
to the battery on the right, which adds its own 6
volts to create a full 12 volts across the load. The
red and blue lines indicate volt meter leads, and
the numbers show the reading that should be
observed on the meter.

In the second schematic, the battery on the left
has become exhausted and is now a dead
weight in the circuit, indicated by its gray color.
The battery on the right still sustains a 6-volt potential. If the internal resistance of the dead battery is approximately 1 ohm and the resistance
of the load is approximately 20 ohms, the potential across the dead battery will be about 0.3 volts,
in the opposite direction to its normal charged
voltage. Reverse charging will result and can
damage the battery. To avoid this problem, a
battery pack containing multiple cells should
never be fully discharged.

High Current Flow Between Parallel
Batteries
If two batteries are connected in parallel, with
correct polarity, but one of them is fully charged
while the other is not, the charged battery will
attempt to recharge its neighbor. 

# Jumper

The spacing between the sockets in a jumper is
referred to as its pitch.

# Fuse

When high current melts a fuse, it is said to blow
or trip the fuse. (In the case of a resettable fuse,
only the word trip is used.)

A fuse responds only to current, not to voltage.

a safe ruleis to figure the maximum amperage when all
components are functioning and add 50%.

However, if current surges or spikes are likely, their
duration will be relevant. If I is the current surge in amps and t is its duration in seconds, the surge
sensitivity of a fuse which is often referred to
verbally or in printed format as I2t is given by
the formula: I2t = I^2 * t

Some semiconductors also have an I2t rating,
and should be protected with a similarly rated
fuse.

Any fuse will present some resistance to the current flowing through it. Otherwise, the current
would not generate the heat that blows the fuse.

Ideally a fuse should function reliably and indefinitely at its rated maximum amperage, but
should blow just as reliably if the current rises by
approximately 20% beyond the maximum. In reality, manufacturers recommend that continuous loading of a fuse should not exceed 75% of
its rating at 25 degrees Centigrade.

The voltage rating or rated voltage of a fuse is the
maximum voltage at which its element can be
counted on to melt in a safe and predictable
manner when it is overloaded by excess current.
Above that rating, the remaining pieces of the
fuse element may form an arc that sustains some
electrical conduction.

A fuse can always be used at a lower voltage than
its rating. If it has a breaking capacity of 250V, it
will still provide the same protection if it is used
at 5V.

Properly known as a polymeric positive temperature coefficient fuse (often abbreviated PTC or
PPTC), a resettable fuse is a solid-state, encapsulated component that greatly increases its resistance in response to a current overload, but gradually returns to its original condition when the
flow of current is discontinued.When more than the maximum current passes
through the fuse, its internal resistance increases
suddenly from a few ohms to hundreds of thousands of ohms. This is known as tripping the fuse.
A resettable fuse contains a polymer whose crystalline structure is loaded with graphite particles
that conduct electricity. As current flowing
through the fuse induces heat, the polymer transitions to an amorphous state, separating the
graphite particles and interrupting the conductive pathways. A small current still passes
through the component, sufficient to maintain
its amorphous state until power is disconnected.
Resettable fuses are used in computer power
supplies, USB power sources, and loudspeaker
enclosures, where they protect the speaker coils
from being overdriven. They are appropriate in
situations where a fuse may be tripped relatively
often.
Brand names for resettable fuses include PolySwitch, OptiReset, Everfuse, Polyfuse, and Multifuse. They are available in surface-mount (SMT)
packages or as through-hole components, but
not in cartridge format.
When a fuse in a circuit blows frequently, this is
known as nuisance opening.
The
formally correct procedure to address this problem is to measure the power surge, properly
known as peak inrush current, with an oscilloscope, calculate the I 2 * t of the wave form, and
select a fuse with a rating at least 5 times that
value.
When a through-hole or surface-mount fuse is soldered into place, heat from the soldering process can cause the soft metal element inside the
fuse to melt partially and reflow. This is likely to
change the rating of the fuse.

# Pushbutton

SPST, also known as 1P1T
Single pole, single throw
DPST also known as 2P1T
Double pole, single throw
SPDT also known as 1P2T
Single pole, double throw
3PST also known as 3P1T
Three pole, single throw
On-Off Behavior
Parentheses are used to indicate the momentary
state of the pushbutton while it is pressed. It will
return to the other state by default.

OFF-(ON) or (ON)-OFF
Contacts are normally open by default, and
are closed only while the button is pressed.
This is sometimes described as a make-to-
make connection, or as a Form A pushbutton.
ON-(OFF) or (OFF)-ON
Contacts are normally closed by default, and
are open only while the button is pressed.
This is sometimes described as a make-to-
break connection, or as a Form B pushbutton.
ON-(ON) or (ON)-ON
This is a double-throw pushbutton in which
one set of contacts is normally closed. When
the button is pressed, the first set of contacts is opened and the other set of contacts is
closed, until the button is released. This is
sometimes described as a Form C pushbutton.
## Latching
This variant, also known as a press-twice pushbutton, contains a mechanical ratchet, which is
rotated each time the button is pressed. The first
press causes contacts to latch in the closed state.

The second press returns the contacts to the
open state, after which, the process repeats. This
press-twice design is typically found on flashlights, audio equipment, and in automotive applications. While latching is the most commonly
used term, it is also known as push-push, locking, push-lock push-release, push-on push-off, and
alternate.

## Radio Buttons
The term radio buttons is sometimes used to
identify a set of pushbuttons that are mechani­
cally interlinked so that only one of them can
make an electrical connection at a time. If one
button is pressed, it latches. If a second button is
pressed, it latches while unlatching the first but­
ton. The buttons can be pressed in any sequence.
This system is useful for applications such as
component selection in a stereo system, where
only one input can be permitted at a time. How­
ever, its use is becoming less common.

When a pushbutton controls a device that has a
high inductive load, a snubber can be added to
minimize arcing.

## Snap-Action
Also known as a limit switch and sometimes as a
microswitch or basic switch. This utilitarian design
is often intended to be triggered mechanically
rather than with finger pressure, for example in
3D printers. It is generally cheap but reliable.

## Rocker
Three rocker switches are shown in Figure 6-6. A
sectional view of a rocker switch is shown in
Figure 6-7. In this design, a spring-loaded ball
bearing rolls to either end of a central rocker arm
when the switch is turned. Rocker switches are
often used as power on-off switches.

![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_17h06m.png)

## Toggle Switch
![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_17h10m.png)


## SIP & DIP
![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_17h15m.png ) ![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_17h15xcm.png)

An application for two limit switches with a DC
motor and two rectifier diodes is shown in
Figure 6-20. This diagram assumes that the mo­
tor turns clockwise when its lower terminal is
positive, and counter-clockwise when its upper
terminal is positive. Only two terminals are used
(and shown) in each limit switch; they are chosen
to be normally-closed. Other terminals inside a
switch may exist, may be normally-open, and can
be ignored.
The motor is driven through a dual-coil, DPDT
latching relay, which will remain in either posi­tion indefinitely without drawing power. When
the upper coil of the relay receives a pulse from
a pushbutton or some other source, the relay
flips to its upper position, which conducts posi­
tive current through the lower limit switch, to the
lower terminal of the motor. The motor turns
clockwise until the arm attached to its shaft hits
the lower limit switch and opens it. Positive cur­
rent is blocked by the lower diode, so the motor
stops.
When the lower coil of the relay is activated, the
relay flips to its lower position. Positive current
can now reach the upper side of the motor
through the upper limit switch. The motor runs
counter-clockwise until its arm opens the upper
limit switch, at which point the motor stops
again. This simple system allows a DC motor to
be run in either direction by a button-press of any
duration, without risk of burnout when the mo­
tor reaches the end of its travel. It has been used
for applications such as raising and lowering
powered windows in an automobile.
![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_17h24m.png)

## Deviatore




![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_17h30m.png)

## Arcing
In DC circuits, arcing can be re­
duced by using a rectifier diode in parallel with
the load (with its polarity blocking normal cur­
rent flow). This is often referred to as a flyback
diode or freewheeling diode. In AC circuits, where
a diode cannot be used in this way, a snubber (a
simple combination of capacitor and resistor)
may be placed around the load.

# Rotary Switch
Also, while the output from a rotational
encoder must be decoded and interpreted by a
device such as a microcontroller, a rotary switch
is an entirely passive component that does not
require any additional electronics for its func­
tionality.
## Rotary DIP Switch
![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_17h43m.png )

## Pushwheel and Thumbwheel
A pushwheel switch is a simple electromechanical
device that enables an operator to provide a
code number as input to data processing equip­
ment, often in industrial process control. 
The
decimal version contains a wheel on which num­
bers are printed, usually in white on black, from
0 through 9, visible one at a time through a win­
dow in the face of the switch.
 A button above the
wheel, marked with a minus sign, rotates it to the
next lower number, while a button below the
wheel, marked with a plus sign, rotates it to the
next higher number. 
A connector at the rear of
the unit includes a common (input) pin and four
output pins with values 1, 2, 4, and 8. An addi­
tional set of pins with values 1, 2, 3, and 4 is often
provided. 
The states of the output pins sum to
the value that is currently being displayed by the
wheel. 
Often two, three, or four pushwheels
(each with an independent set of connector pins)
are combined in one unit, although individual
pushwheels are available and can be stacked in
a row.

A thumbwheel switch operates like a pushwheel
switch, except that it uses a thumbwheel instead
of two buttons. Miniaturized thumbwheel
switches are available for through-hole mount­
ing on PC boards.

# Rotational Encoder
However, the term rotational encoder is now applied to almost any device
capable of converting rotational position to a digital output via opening and closing
internal mechanical contacts; 

Any mechanical switch will suffer some degree
of contact bounce when its contacts close. Data­
sheets for rotational encoders may include a
specification for bounce duration ranging from
around 2ms to 5ms, which is sometimes known
as the **settling time**.

# Relays
![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_18h20m.png)
##Variants
###Latching
There are two basic types of relay: latching and
nonlatching. A nonlatching relay, also known as
a single side stable type, is the most common, and
resembles a momentary switch or pushbutton
in that its contacts spring back to their default
state when power to the relay is interrupted. This
can be important in an application where the re­
lay should return to a known state if power is lost.
By contrast, a latching relay has no default state.
Latching relays almost always have double-
throw contacts, which remain in either position
without drawing power. The relay only requires
a short pulse to change its status. In semicon­
ductor terms, its behavior is similar to that of a
flip-flop.
##Contactor
A contactor functions just like a relay but is de­
signed to switch higher currents (up to thou­
sands of amperes) at higher voltages (up to many
kilovolts). 

The minimum voltage that the
relay needs for activation is sometimes described
as the Must Operate By voltage, while the Must
Release By voltage is the maximum coil voltage
that the relay will ignore. 

A circuit including every possible protection
against voltage spikes is shown in Figure 9-13,
including a snubber to protect the relay contacts,
a rectifier diode to suppress back-EMF generated
by the relay coil, and another rectifier diode to

protect the relay from EMF generated by a motor
when the relay switches it on and off. The snub­
ber can be omitted if the motor draws a relatively
low current (below 5A) or if the relay is switching
a noninductive load. The diode around the relay
coil can be omitted if there are no semiconduc­
tors or other components in the circuit that are
vulnerable to voltage spikes. However, a spike
can affect components in adjacent circuits that
appear to be electrically isolated. 

![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_19h09m.png)

#Resistor
Resistor arrays with isolated or common-bus
configurations are a convenient way to reduce
the component count in circuits where pullup,
pulldown, or terminating resistors are required
for multiple chips.


The traditional range of resistor values was es­
tablished when a tolerance of 20% was the norm.
The values were spaced to allow minimum risk of
a resistor at one end of its tolerance range having
the same value as another resistor at the oppo­
site end of its tolerance range. The values were
rounded to 10, 15, 22, 33, 47, 68, and 100,

A surface-mount resistor with a single zero print­
ed on it is a zero ohm component that has the
same function as a jumper wire. It is used for
convenience, as it is easily inserted by automated
production-line equipment. It functions merely
as a bridge between traces on the circuit board.

## Usage
* In Series with LED
* Current Limiting with a Transistor (Base current)
* Pullup and Pulldown Resistors
* Audio Tone Control
* RC network
* Voltage Divider

The wattage rating of a resistor does not neces­
sarily mean that it should be used to dissipate
that amount of power on a constant basis. Small
resistors (1/4 watt or less) can overheat just as
easily as big ones. Generally speaking, it is safe
practice not to exceed 75% of a resistor’s power
rating on a constant basis.

# Potentiometer
To use a potentiometer as a variable resistor or
rheostat, one of its end terminals may be tied to
the center terminal. If the unused end terminal is
left unconnected, this raises the risk of picking
up stray voltages or “noise” in sensitive circuits.

![](file:///C:/Users/f126ck/Desktop/markEd/04October2019_19h39m.png)

##Ganged Potentiometer
Two (or rarely, more) potentiometers can be
stacked or combined so that their resistive ele­
ments and wipers share the same shaft but can
use different voltages or have different taper.
Each resistance-wiper assembly is known as a
cup, and the potentiometers are said to be
ganged.

##Switched Potentiometer
In this variant, when the shaft is turned clockwise
from an initial position that is fully counter-
clockwise, it flips an internal switch connected to
external terminals. This can be used to power-up
associated components (for example, an audio
amplifier). Alternatively, a switch inside a poten­
tiometer may be configured so that it is activated
by pulling or pushing the shaft.

# Capacitor
Capacitor networks can reduce the component
count in circuits where digital logic chips require
bypass capacitors. They are comparable in con­
cept to resistor arrays.
Tantalum capacitors are compact but relatively
expensive, and can be vulnerable to voltage
spikes. They are sensitive to application of the
wrong polarity. Typically they are epoxy-dipped
rather than mounted inside a small aluminum
can like electrolytics, and consequently the elec­
trolyte may be less likely to evaporate and dry
out. 
##Dielectrics
Polyester
This is the most common type of plastic film,
with the highest dielectric constant, ena­
bling highest capacitance per unit volume.
Widely used in DC applications, but the rol­
led layers create parasitic inductance. Often
used in decoupling, coupling, and bypass,
but not so suitable for situations requiring
stability and low leakage. May not be suit­
able for high current.
Polycarbonate
Thermally very stable, often specified for fil­
ters and timing circuits that require a fixed
frequency. An excellent type of capacitor,
compatible for mil-spec applications, but ex­
pensive.
##Equivalent Series Resistance
A theoretically ideal capacitor would be purely
reactive, without any resistance. In reality, capac­
itors are not ideal, and they have equivalent series
resistance, or ESR. This is defined as the resistor that you would have to place in series with an
ideal version of the capacitor, so that the combi­
nation would behave like the real version of the
capacitor on its own.
If X c is the reactance of the capacitor, then its Q
factor (which means its quality factor) is given by
the simple formula:
Q = Xc / ESR
## Usage
### Bypass capacitor
In Figure 12-19, a low-value capacitor (often
0.1μF) is placed near the power input pin of a
sensitive digital chip to divert high-frequency
spikes or noise to negative ground.
### Coupling Capacitor
a 1μF coupling capacitor trans­
mits a pulse from one section of a circuit to an­
other, while blocking the DC voltage. Some re­
shaping of the waveform may occur.
### High pass filter
### Low pass filter

### Smoothing capacitor
used in power sources
### Snubber
an RC network (inside a white
dashed line) is known as a snubber when used to
protect a switch from the problem of arcing (pro­
nounced “arking”)—that is, a sustained spark
that can quickly erode the switch contacts. Arc­
ing may occur in switches, pushbuttons, or relays

When the switch is opened, the magnetic field
that has been sustained by the inductive load
collapses, causing a surge of current, or forward
EMF. The capacitor in the snubber absorbs this
surge, thus protecting the switch contacts. When
the switch is closed again, the capacitor dis­
charges itself, but the resistor limits the outrush
of current—again, protecting the switch.
In an AC circuit, a snubber can be placed around
the inductive load itself. Although a diode is
often used this way in a DC circuit, it cannot be
used with AC.

###Vibration
In a high-vibration environment, electrolytics
should be protected by clamping them mechan­
ically in place, using a capacitor clamp, also
known as a c-clamp.

# Variable Capacitor
Small trimmer capacitors are widely available and
are mostly used to adjust high-frequency cir­
cuits. Many of them look almost indistinguisha­
ble from trimmer potentiometers.
In addition to tuning a circuit frequency, a trim­
mer capacitor can be used to compensate for
changes in capacitance or inductance in a circuit
that are caused by the relocation of wires or re­
routing of traces during the development pro­
cess. Readjusting a trimmer is easier than swap­
ping fixed-value capacitors. A trimmer may also
be used to compensate for capacitance in a cir­
cuit that gradually drifts with age.
Although trimmer capacitors are not polarized,
the manufacturer may mark one terminal with a
plus sign and/or the other with a minus sign. If
the capacitor is adjusted while its negative ter­
minal is floating or ungrounded, a metal screw­
driver blade will create erroneous readings. Al­
ways ground the appropriate side of a trimmer
capacitor before fine-tuning it, and preferably
use a plastic-bladed screwdriver.
# Inductor
An inductor is a coil that induces a magnetic field
in itself or in a core as a result of current passing
through the coil. It may be used in circuits to
block or reshape AC current or a range of AC fre­
quencies, and in this role can “tune” a simple ra­
dio receiver or various types of oscillators. It can
also protect sensitive equipment from destruc­tive voltage spikes.
##Magnetic core
One major disadvantage of a magnetic core is
hysteresis, which in this context refers to the ten­
dency of the core to retain some magnetic
“memory” as a cycle of alternating current
changes from positive to negative. This residual
magnetism must be overcome by the next posi­
tive pulse of AC. The tendency of the core to re­
tain magnetic polarity is known as its retentivity.
Iron cores are especially retentive.
Another disadvantage of some magnetic cores is
that they may host eddy currents induced by the
magnetic field of the coil. These electrical cur­
rents tend to circulate through the core, reducing
efficiency by generating waste heat, especially if
coil currents are high.
Powdered iron inhibits eddy currents because the particles have
limited contact.
Ferrites are nonconductive, and
are therefore immune to eddy currents. They are
widely used.
tive voltage spikes
##Nonmagnetic Cores
The problems associated with magnetic cores
may be avoided by winding the coil around a
nonmagnetic core that may be hollow, ceramic,
or plastic. A hollow core is referred to as an air
core. The permeability of ceramic and plastic
cores is close to that of air.
##Variable Inductors
A variable inductor, also known as an adjustable
inductor, is relatively uncommon but can be fab­
ricated by using a magnetic core that penetrates
the center of the inductor on an adjustable screw
thread. The inductance of the assembly will in­
crease as a larger proportion of the magnetic
core penetrates into the open center of the coil.
##Ferrite Beads
A ferrite bead inverts the design of a typical in­
ductor by running a wire through a hole in the
center of the bead, instead of coiling the wire
around the core.
The purpose is either to limit radio-frequency ra­
diation from a wire by absorbing it into the bead
(where it is transformed into heat), or to protect
a wire from external sources of radio-frequency
radiation. Computer cabling to external devices;
lamp dimmers; and some types of motors can be
sources of radio frequency.
##Toroidal Cores
The magnetic circuit created by a rod-shaped
core must be completed by the lines of force
traveling back around from one end of the rod to
the other, through the surrounding air. Since air
has low permeability, this is a major source of inefficiency. By comparison, a torus (a geometrical
shape resembling a donut) completes the entire
magnetic circuit inside its core. This significantly
increases its efficiency. Also, because its field is
better contained, a toroidal inductor needs little
or no shielding to protect other components
from stray magnetic effects.
##Gyrator
A gyrator is a small network, sometimes encap­
sulated in a silicon chip, using resistors, a semi­
conductor, and a capacitor to simulate some but
not all of the behavior of a coil-based inductor.
The semiconductor may be a transistor or a ca­
pacitor, depending on the specific circuit. A sam­
ple schematic is shown in Figure 14-18. Because
no magnetic effects are induced, the gyrator is
completely free from the problems of saturation
and hysteresis, which affect coils with cores, and
also produces no back-EMF. It simply attenuates
a signal initially, and then gradually lowers its re­
actance, thus imitating this aspect of an inductor.
![](file:///C:/Users/f126ck/Desktop/markEd/05October2019_17h09m.png)
However, the performance
advantages of gyrators are significant, as they
can emulate high inductance without parasitic
effects, can be more accurately calibrated (lead­
ing to more predictable performance), and do
not create magnetic fields that can interfere with
other components.
A typical manufacturer’s datasheet should in­
clude an inductance index for an inductor, ex­
pressed in μH per 100 turns of wire (assuming the
wire is in a single layer) for inductors with a pow­
dered iron core, and mH per 1,000 turns of wire
for inductors with ferrite cores.
The DCR is the DC resistance of an inductor, de­
rived purely from the wire diameter and its
length.
The SRF is the self-resonant frequency. An induc­
tor should be chosen so that AC current passing
through it will never get close to that frequency.
ISAT (or I sat ) is the saturation current, which re­
sults in a magnetic core losing its function as a
result of magnetic saturation. When this occurs,
inductance drops and the charge current rate in­
creases drastically.
An inductor can be combined with a capacitor to
form a bandpass filter,
![](file:///C:/Users/f126ck/Desktop/markEd/05October2019_17h25m.png)
Once again if the location of the components is
shifted to shunt the signal away from the output,
the results are reversed, as shown in
Figure 14-25. This is known as a notch filter.
#Transformer
When the transformer is not loaded, the primary
winding behaves like a simple inductor with re­
actance that inhibits the flow of current. There­
fore a power transformer will consume relatively
little electricity if it is left plugged in to an elec­
trical outlet without any load connected to its
output side. The power that it does consume will
be wasted as heat.

##Taps
A tap on a transformer is a connection part-way
through the primary or (more often) the secon­
dary coil. On the primary side, applying an input
between the start of a coil and a tap part-way
through the coil will reduce the number of turns
to which the voltage is applied, therefore in­
creasing the ratio of output turns to input turns,
and increasing the output voltage. On the sec­
ondary side, taking an output between the start
of a coil and a tap part-way through the coil will
reduce the number of turns from which the volt­
age is taken, therefore decreasing the ratio of
output turns to input turns, and decreasing the
output voltage. This can be summarized:
* A tap on the primary side can increase out­
put voltage.
* A tap on the secondary side can provide a
decreased output voltage.
f the winding on the primary side of a trans­
former is coiled in the same direction as the
winding on the secondary side, the output volt­
age will be 180 degrees out of phase with the input voltage. 
##Isolation Transformer
Also known as a 1:1 transformer because it has a
1:1 ratio between primary and secondary wind­
ings, so that the output voltage will be the same
as the input voltage. When electrical equipment
is plugged into the isolation transformer, it is
separated from the electrical ground of AC pow­
er wiring. This reduces risk when working on “live” equipment, as there will be negligible elec­
trical potential between itself and ground. Con­
sequently, touching a grounded object while al­
so touching a live wire in the equipment should
not result in potentially lethal current passing
through the body.
##Autotransformer
This variant uses only one coil that is tapped to
provide output voltage. Mutual induction occurs
between the sections of the coil. An autotrans­
former entails a common connection between
its input and output, unlike a two-coil transform­
er, which allows the output to be electrically iso­
lated from the input. See Figure 15-10. Auto­
transformers are often used for impedance
matching in audio circuits, and to provide output
voltages that differ only slightly from input vol­
tages.
# AC-DC power supply
Switching Power Supply Also known as a switched-mode power supply, an SMPS, or switcher, it converts AC to DC in two stages.
1. A rectifier changes the AC input to unsmoothed DC, without a power transformer.
2. A DC-DC converter switches the DC on and off at a very high frequency using pulsewidth modulation to reduce its average effective voltage. Often the converter will be the flyback type, containing a transformer, but the high-frequency switching allows the transformer to be much smaller than the power transformer required in a linear regulated power supply. See the DC-DC converter entry in this encyclopedia for an explanation of the working principles

# DC-DC converter
A DC-DC converter, often referred to simply as a converter, receives a DC voltage as its input and converts it to a regulated DC voltage as its output.
The output voltage may be higher or lower than the input voltage, may be user-adjustable by adding an external resistor, and may be completely electrically isolated from the input, depending on the type of converter that is used.
A DC-DC converter is an integrated circuit package that includes a high-speed switching device (almost always, a MOSFET) in conjunction with an oscillator circuit, an inductor, and a diode.
By comparison, a linear regulator is usually based around bipolar transistors. Its input must always be at a higher voltage than its output, and its efficiency will be inversely proportional with the voltage drop that it imposes.
An internal oscillator controls a MOSFET semiconductor that switches the DC input on and off at a high frequency, usually from 50KHz to 1MHz.
Output voltage is adjusted by varying the duty cycle of the oscillator—the length of each “on” pulse relative to each “off” interval (PWM).
The duty cycle is controlled by sampling the output of the converter and using a comparator to subtract the output voltage from a reference voltage, to establish an error value. This is passed to another comparator, which subtracts the error voltage from an oscillator ramp signal. If the error increases, the oscillator signal is more heavily clipped, thus changing the effective ratio of on/off pulse lengths. 
![](file:///C:/Users/f126ck/Desktop/markEd/06October2019_18h24m.png)
The key to the efficiency of a DC-DC converter is an inductor, which stores energy in its magnetic field during “on” pulse and releases it in the discharge phase. Thus, the inductor is used as a temporary reservoir and minimizes the ripple current. All converter variants use a coil for this purpose, although its placement varies in relation to the diode and capacitor that complete the basic circuit.
variable D is the duty cycle in the pulse train generated through an internal MOSFET switch. The duty cycle is the fraction of the total on-off cycle that is occupied by each “on” pulse. In other words, if
Ton is the duration of an “on” pulse and Toff is the “off” time: 
D = Ton / ( Ton + Toff )
##Buck Converter
 See Figure 17-3. The output voltage is lower than the input voltage. The input and output share a common ground. For this circuit: 
Vout = Vin * D
![](file:///C:/Users/f126ck/Desktop/markEd/06October2019_18h28m.png)
## Boost Converter
 See Figure 17-4. The output voltage is greater than the input voltage. The input and output share a common ground. For this circuit: 
Vout = Vin / (1-D)
![](file:///C:/Users/f126ck/Desktop/markEd/06October2019_18h29m.png)
## Flyback Converter with Inductor
Commonly known as a *buck-boost converter*. See Figure 17-5. The output voltage can be less than or greater than the input voltage. The input and output share a common ground. For this circuit:
Vout = Vin * ( D / ( 1 - D) )
![](file:///C:/Users/f126ck/Desktop/markEd/06October2019_18h31m.png)
## Flyback Converter with Transformer 
See Figure 17-6. The output voltage can be less than or greater than the input voltage. The input and output are isolated from one another. For this circuit:
Vout = Vin * ( D / ( 1 - D) )
![](file:///C:/Users/f126ck/Desktop/markEd/06October2019_18h32m.png)
Using a transformer in the converter allows multiple outputs with different voltages, supplied through multiple transformer windings.
On a circuit board that is primarily populated with 5VDC components and is fed by a single 5VDC power supply, a converter can be used to supply 12VDC for one special purpose, such as an analog-digital converter or a serial data connection.
# DC-AC inverter
he inverter receives an input of direct current (typically 12VDC from a car battery) and delivers an output of alternating current (AC) in the range 110VAC-120VAC or 220VAC-240VAC, suitable to power many lowwattage appliances and devices.
The first stage of an inverter typically raises a 12VDC input to a higher DC voltage via an internal DC-DC converter, then uses a switching circuit to create an approximation of the sinusoidal profile that is characteristic of AC voltage.
The RMS value is important as a means to calculate actual power delivered because it can be multiplied by the current to obtain an approximate value in watts.
![](file:///C:/Users/f126ck/Desktop/markEd/06October2019_18h46m.png)
As a first step toward a better approximation of a sine wave, gaps of zero voltage can be inserted between square-wave pulses. This “gapped” square wave is shown in Figure 18-3.
![](file:///C:/Users/f126ck/Desktop/markEd/06October2019_18h47m.png)
# Voltage Regulator
A linear voltage regulator provides a tightly controlled DC output, which it derives from an unregulated or poorly regulated DC input. The DC output remains constant regardless of the load on the regulator (within specified limits). It is a cheap, simple, and extremely robust.
Some voltage regulators include an extra pin, typically known as an enable pin, which switches off the device in response to a signal from a microcontroller or logic gate. Some regulators offer another option, an additional status pin that can signal a microcontroller that an error mode exists if the regulator output falls significantly below its rated value.
A linear voltage regulator cannot respond instantly to changes in input voltage. Therefore, if the input supply contains voltage spikes, these spikes may pass through the regulator. Bypass capacitors should be applied preventively. component.
All linear regulators function by taking some feedback from the output, deriving an error value by comparing the output with a reference voltage (most simply provided by a zener diode), 
and using the error value to control the base of a pass transistor that is placed between the input and the output of the regulator. Because the transistor operates below saturation level, its output current varies linearly with the current applied to its base, and this behavior gives the linear regulator is name.
The voltage difference required between the base and emitter of an NPN transistor is a minimum of 0.6V. Because multiple transistors are used inside a standard-type voltage regulator, it requires a minimum total voltage difference, between its input and its output, of 2VDC. This voltage difference is known as the dropout voltage. If the voltage difference falls below this minimum, the regulator ceases to deliver a reliable output voltage until the input voltage rises again. Low dropout regulators allow a lower voltage difference, but are more expensive and less commonly used.
![](file:///C:/Users/f126ck/Desktop/markEd/06October2019_20h05m.png)
## Adjustable Regulators
 While the majority of regulators have a fixed output, some allow the user to set the output by adding one or more resistors.
The LM317 is a popular example.
Its output voltage can range from 1.25VDC to 37VDC and is set via a resistor and a trimmer potentiometer.
Vout, is given by the formula Vout = 1.25 * ( 1 + ( R2/R1 ) )
## Negative and Positive Regulators
 While most linear voltage regulators are designed for “positive input” (conventional current flow from input to output), some are intended for “negative input.” In this variant, the common terminal is positive, and the input and output are negative in relation to it.
## Low-Dropout Linear Regulators
Low-dropout regulators (sometimes referred to as LDO regulators) allow a much lower dropout voltage by using a single PNP or MOSFET transistor. LDO regulators are popularly used in battery-powered devices where efficiency should be maximized and heat dissipation should be minimized. For example, the LM330 is
## Transient Response 
When there is a major fluctuation in the demand by the load (for example, if an inductive device is switched on elsewhere in the circuit), the voltage regulator requires a finite time to adjust itself and maintain its specified output voltage. This time lag is known as its transient response.
sing an LM7808 instead of an LM7805 may be sufficient to destroy all the 5VDC chips in a logic circuit.
The LM78xx series of voltage regulators uses a very intuitively obvious and consistent scheme for the functions of its pins: input on the left, ground in the center, and output on the right, when looking at the regulator from the front, with its pins facing downward.
##Inaccurate Delivered Voltage 
A voltage regulator maintains its output voltage between its output pin and ground pin. Thin traces on a circuit board, or a long run of very small-gauge wiring, can impose some electrical resistance, reducing the actual voltage delivered to a component.
For example, if the resistance between the output pin of a voltage regulator and a component is 0.5Ω and the current is 0.1A, the voltage drop will be only 0.05V. But if the current increases to 1A, the voltage drop is now 0.5V.

# Electromagnets
When an electromagnet is energized by alternating current, it can be used to degauss (in other words, to demagnetize) other objects
The AC is either applied with diminishing current, so that the alternating magnetic polarities gradually subside to zero, or the electromagnet is gradually moved away from the target, again reducing the magnetic influence to (virtually) zero. This latter procedure may be used periodically to demagnetize record and replay heads on tape recorders, which otherwise tend to acquire residual magnetism, inducing background hiss on the tape.
A solenoid with a nonmagnetized plunger may be energized by AC current, since polarity reversals in the magnetic field generated by the coil will induce equal and opposite reversals in the polarity of the plunger. However, the force curve of an AC-powered solenoid will be different from the force curve of a DC-powered solenoid. See Figure 21-5. The alternating current is likely to induce humming, buzzing, and vibration.
The heat generated by a solenoid when it is maintained in its energized state may be reduced if the manufacturer includes a series resistor and a switch that functions as a bypass switch. The switch is normally closed, but is opened mechanically when the plunger reaches the end of its throw, thus diverting electricity through the series resistor. This itself will generate some heat as a result of the current flowing through it, but by increasing the total resistance of the system, the total heat output will be reduced. The resistor value is chosen to provide the minimum power needed to retain the plunger at the end of its throw.
Suppose a solenoid is rated for a 25% duty cycle. If the solenoid is appropriately switched on for one second and off for three seconds, the heat will be allowed to dissipate before it has time to reach overload levels. If the solenoid is switched on for one minute and off for three minutes, the duty cycle is still 25%, but the heat that may accumulate during a one-minute “on” cycle may overload the component before the “off” cycle can allow it to dissipate.
When an AC solenoid reaches the end of its travel, the sudden stop of the plunger results in forward EMF that generates additional heat. Generally speaking, a longer stroke creates a greater surge. Rapid cycling will therefore exacerbate coil heating.

# DC Motor
Generally speaking, the delta configuration is best suited to high-speed applications, but provides relatively low torque at low speed. The wye configuration provides higher torque at low speed, but its top speed is limited.
In reality, the reduction can be expected to have a fractional component. This is because if two gears have an integer ratio, their operating life will be shortened, as a manufacturing defect in a tooth in the smaller gear will hit the same spots in the larger gear each time it rotates. For this reason, the numbers of teeth in two spur gears usually do not have any common factors (as in the example above), and if a motor rotates at 500 RPM, a gear ratio stated as 50:1 is very unlikely to produce an output of exactly 10 RPM.
Planetary gears are used primarily if a motor drives a heavy load, as the force is divided among more gear pairs, reducing wear and tear on gear teeth and minimizing the breakdown of lubrication.
![](file:///C:/Users/f126ck/Desktop/markEd/27October2019_12h38m.png)
##Speed Control
 A rheostat or potentiometer may be placed in series with a traditional DC motor to adjust its speed, but will be inefficient, as it will achieve a voltage drop by generating heat. Any rheostat must be rated appropriately, and should probably be wire-wound. The voltage drop between the wiper and the input terminal of the rheostat should be measured under a variety of operating conditions, along with the amperage in the circuit, to verify that the wattage rating is appropriate.
## Direction Control 
The H bridge is a very early system for reversing the direction of a DC motor simply by swapping the polarity of its power supply appropriate.
This is obviously a primitive scheme, but the term “H bridge” is still used when prepackaged in a single chip such as the LMD18200 H bridge motor controller from National
## Backlash
 Backlash is the looseness or “slack” in a gear train that results from small gaps between meshing gear teeth. Because backlash is cumulative when gears are assembled in series, it can become significant in a slow-output gearhead motor. When measured at the output shaft, it is generally in the range of 1 to 7 degrees, tending to increase as the load increases. If a geared motor is used as a positioning device, and is fitted with an encoder to count rotations of the motor shaft, control electronics may cause the motor to hunt to and fro in an attempt to overcome the hysteresis allowed by the backlash. A stepper motor or servo motor is probably better suited to this kind of application. Semiconductor.
#Single-Phase Induction Motor
 The majority of induction motors run on singlephase alternating current (typically, from domestic wall outlets). This type of motor is not innately self-starting because the stator coils and rotor are symmetrical. This tends to result in vibration rather than rotation
To initiate rotation, the stator design is modified so that it induces an asymmetrical magnetic field, which is more powerful in one direction than the other. The simplest way to achieve this is by adding one or more shorting coils to the stator. Each shorting coil is often just a circle of heavygauge copper wire. This ploy reduces the efficiency of the motor and impairs its starting torque, and is generally used in small devices such as electric fans, where low-end torque is unimportant. Because the shorting coil obstructs some of the magnetic field, this configuration is often known as a shaded pole motor.
A capacitor is a higher-cost but more efficient alternative to a shorting coil. If power is supplied to one or more of the stator coils through a capacitor, it will create a phase difference between these coils and the others in the motor, inducing an asymmetrical magnetic field. When the motor reaches approximately 80% of its designed running speed, a centrifugal switch may be included to take the capacitor out of the circuit, since it is no longer necessary. Switching out the capacitor and substituting a direct connection to the stator coils will improve the efficiency of the motor.
A third option to initiate rotation is to add a second winding in the stator, using fewer turns of smaller-gauge wire, which have a higher resistance than the main winding. Consequently the magnetic field will be angled to encourage the motor to start turning. This configuration is known as a split-phase induction motor, in which the starter winding is often referred to as the auxilliary winding and consists of about 30% of the total stator windings in the motor. Here again, a centrifugal switch can be incorporated, to eliminate the secondary winding from the circuit when the motor has reached 75 to 80 percent of its designed running speed.
## VFD Variable Frequency Drive
The advent of cheap solid-state technology encouraged the development of variable-frequency power supplies for induction motors. Because the impedance of the motor will diminish as the frequency diminishes, the current drawn by the motor will tend to increase. To prevent this, a variable frequency supply also varies the voltage that it delivers.
##Wound-Rotor AC Induction Motor 
The stator of this variant is basically the same as that of a single-phase induction motor, but the rotor contains its own set of coils. These are electrically accessible via a commutator and brushes, as in a DC motor. Because the maximum torque (also known as pull-out torque) will be proportional to the electrical resistance of the coils in the rotor, the characteristics of the motor can be adjusted by adding or removing resistance externally, via the commutator. A higher resistance will enable greater torque at low speed when the slip between the rotor speed and rotation of the magnetic field induced by the stator is greatest. This is especially useful in corded power tools such as electric drills, where high torque at low speed is desirable, yet the motor can accelerate to full speed quickly when the external resistance is reduced. Typically, the resistance is adjusted via the trigger of the drill.
## Universal Motor
 A wound-rotor motor may also be described as a universal motor if its rotor and stator coils are connected in series. This configuration allows it to be powered by either AC or DC.
##Premature Restart
 Large industrial three-phase induction motors can be damaged if power is reapplied before the motor has stopped rotating.
##Frequent Restart
 If a motor is stopped and started repeatedly, the heat that is generated during the initial surge of current is likely to be cumulative.
##Undervoltage or Voltage Imbalance 
A voltage drop can cause the motor to draw more current than it is rated to handle. If this situation persists, overheating will result. Problems also are caused in a three-phase motor where one phase is not voltage-balanced with the others. The most common cause of this problem is an open circuit-breaker, wiring fault, or blown fuse affecting just one of the three conductors. The motor will try to run using the two conductors that are still providing power, but the result is likely to be destructive.
##Stalled Motor
When power is applied to an induction motor, if the motor is prevented from turning, the conductors in the rotor will carry a large current that is entirely dissipated as heat. This current surge will either burn out the motor or blow a fuse or circuit breaker. Care should be taken, in equipment design, to minimize the risk that an induction motor may stall or jam.
##Protective Relays
 Sophisticated protective relays are available for industrial 3-phase motors, and can guard against all of the faults itemized above. Their details are outside the scope of this encyclopedia.
##Excess Torque 
As has been previously noted, the torque of an induction motor increases with the slip (speed difference) between the rotation of the magnetic field and the rotation of the rotor. Consequently, if the motor is overloaded and forced to run more slowly, it can deliver more rotational force. This can destroy other parts attached to the motor, such as drive belts.
##Internal Breakage 
An overloaded induction motor may suffer some cracking or breakage of its rotor. This may be obvious because of reduced power output or vibration, but can also be detected if the motor’s power consumption changes significantly.

# Servo Motor
A servo motor is actually a combination of a motor, reduction gearing, and miniaturized control electronics, usually packaged together inside a very compact sealed plastic case. The motor itself may be AC or DC, and if DC, it may be brushed or brushless. What distinguishes a servo from other types of motor is that it is not designed for continuous rotation. It is a position-seeking device. Its rotational range may be more than 180 degrees but will be significantly less than 360 degrees.
![](file:///C:/Users/f126ck/Desktop/markEd/27October2019_19h35m.png)
Inside a servo motor’s casing, the electronics include a potentiometer that turns with the output shaft, to provide feedback confirming the motor’s position. The limited turning range of the potentiometer determines the turn limits of the motor output shaft.
Karbonite gears are a reinforced plastic composite material used in Hitec RC servos that show almost five times the strength of nylon gears and better wear resistance. Cycle times of over 300,000 have been observed with these gear trains showing virtually no wear. Karbonite-geared servos are more expensive than those using nylon ones but are highly durable.[1] Hobbyists are advised avoid use of thread locking compounds on Karbonite as this will cause the plastic to fail. 
So-called **digital servos** use faster internal electronics than the older, so-called analog servos, and because they sample the incoming pulse stream at a higher frequency, they are more responsive to small, rapid commands from the controller. For this reason they are preferred by hobbyists using servos to control the flight of model airplanes.
A servo generally has three wires, colored red (power supply), black or brown (ground), and orange, yellow, or white (for the pulse train from the controller). The ground wire to the motor must be common with the ground of the controller, and consequently a ceramic bypass capacitor of 0.1μF or 0.01μF should be placed between the (red) power wire to the motor and ground. A protection diode should also be used.
Various shaft attachments are available from the same online hobby-electronics suppliers that sell servos. The attachments include discs, single arms, double arms, and four arms in a crossshaped configuration. A single-arm attachment is often known as a horn, and this term may be applied loosely to any kind of attachment.
![](file:///C:/Users/f126ck/Desktop/markEd/27October2019_19h47m.png)

## Modification for Continuous Rotation
 It is possible to modify a small servo motor so that it will rotate continuously. First the motor case must be opened, and the potentiometer must be centered by using a controller to send some 1.5ms pulses. The potentiometer must then be glued or otherwise secured with its wiper in this precise center position, after which the potentiometer is disconnected from the drive train.
Mechanical stops that would limit the rotation of the motor shaft must be cut away, after which the motor is reassembled. Because the potentiometer has been immobilized, the motor’s internal electronics will now “see” the shaft as being in its center position at all times. If the controller sends a pulse instructing the motor to seek a position clockwise or counter-clockwise from center, the motor will rotate in an effort to reach that position. Because the potentiometer will not provide feedback to signal that the motor has achieved its goal, the shaft will continue to rotate indefinitely.

**The purpose of modifying a servo for continuous rotation is to take advantage of its high torque, small size, light weight, and the ease of controlling it with a microcontroller.**
##Permanent Magnet Stepper Motors 
More commonly, the rotor of a stepper motor contains permanent magnets, which require the controller to be capable of reversing the magnetic field created by each of the stator coils, so that they alternately attract and repel the rotor magnets.
In a bipolar motor, the magnetic field generated by a coil is reversed simply by reversing the current through it. This is shown diagrammatically in Figure 25-3. In a unipolar motor, the magnetic field is reversed by applying positive voltage to the center tap of a coil, and grounding one end or the other. This is shown diagrammatically in Figure 25-4.
![](file:///C:/Users/f126ck/Desktop/markEd/27October2019_20h01m.png)
![](file:///C:/Users/f126ck/Desktop/markEd/27October2019_20h02m.png)

## Bipolar Stepper Motors 
The most basic way to reverse the current in a coil is by using an H-bridge configuration of switches, as shown in Figure 25-8, where the green arrow indicates the direction of the magnetic field. In actual applications, the switches are solid-state. Integrated circuits are available containing all the necessary components to control a bipolar stepper motor.
## Unipolar Motors 
The control electronics for a unipolar motor can be simpler than those for a bipolar motor, as offthe-shelf switching transistors can ground one end of the coil or the other. The classic five-wire unipolar stepper motor, often sold to hobbyists and used in robotics projects and similar applications, can be driven by nothing more elaborate than a set of 555 timer chips.
However, this type of motor is less powerful for its size and weight because only half of each coil is energized at a time.

![](file:///C:/Users/f126ck/Desktop/markEd/28October2019_22h29m.png)


##Multiphase
 In a multiphase motor, multiple stator coils are usually connected in series, with a center tap applied between each pair.
![](file:///C:/Users/f126ck/Desktop/markEd/28October2019_22h50m.png)
The way in which the motor is wired enables only one stator coil to be unpowered during any step, because its two ends are at equal potential. Therefore this type of motor is capable of high torque in a relatively small format.
##Voltage Control 
Rapid stepping of a motor requires rapid creation and collapse of magnetic fields in the stator windings. Therefore, self-inductance of the windings can limit the motor speed. One way to overcome this is to use a higher voltage. A more sophisticated solution is to use a controller that provides a high initial voltage, which is reduced or briefly interrupted when a sensor indicates that coil current has increased sufficiently to overcome the self-inductance of the windings and has reached its imposed limit. This type of controller may be referred to as a chopper drive as the voltage is “chopped,” usually by power transistors. It is a form of pulse width modulation.

![](file:///C:/Users/f126ck/Desktop/markEd/28October2019_22h57m.png)

If a unipolar motor is relatively small and is fitted with five wires, almost certainly the motor contains two coils, each with a center tap, and their function can be determined by applying positive voltage to the red wire and grounding each of the other wires in turn. Attaching a small piece of tape to the motor shaft will assist in viewing its orientation.
A multimeter set to measure ohms can also be useful in deducing the internal coil connections of the motor, since the end-to-end resistance of a coil should be approximately twice the resistance between the center tap and either end of the coil.
A multiphase motor may have five wires, but in this case, the resistance between any two nonadjacent wires will be 1.5 times the resistance between any two adjacent wires.
Resonance A motor has a natural resonant frequency. If it is stepped near that frequency, vibration will tend to be amplified, which can cause positional errors, gear wear (if gears are attached), bearing wear, noise, and other issues. A good datasheet should specify the resonant frequency of the motor, and the motor should run above that frequency if possible. The problem can be addressed by rubber motor mounts or by using a resilient component, such as a drive belt, in conjunction with the drive shaft. Damping the vibration may be attempted by adding weight to the motor mount.
## Hunting
 In a closed-loop system, a sensor on the motor reports its rotational position to the controller, and if necessary, the controller responds by adjusting the position of the motor. Like any feedback system, this entails some lag time, and at certain speeds the motor may start hunting or oscillating as the controller over-corrects and must then correct its correction. Some closedloop controllers avoid this issue by running mostly in open-loop mode, using correction only when the motor experiences conditions (such as sudden speed changes), which are likely to cause step loss.

# Diode
A Zener diode can regulate voltage, a varactor diode can control a high-frequency oscillator, and tunnel diodes, Gunn diodes, and PIN diodes have high-frequency applications appropriate to their rapid switching capability.
Each cylindrical diode is marked with a silver stripe (a black stripe on the 1N4148) to identify its cathode, or the end of the diode that should be “more negative” when the component is forward biased. Peak current can greatly exceed continuous current without damaging the component
In a silicon diode, if the potential difference is greater than approximately 0.6 volts, this is known as the junction threshold voltage, and the charges start to pass through the junction. The threshold is only about 0.2 volts in a germanium diode, while in a Schottky diode it is about 0.4 volts.
The junction is now a depletion region, which blocks current.
When the diode is reverse-biased, it is still not 100% efficient, this time in its task of blocking curernt.

The very small amount of current that manages to get through is known as leakage. This is almost always less than 1mA and may be just a few μA, depending on the type of diode.


One way to remember the meaning of a stripe on the cathode end of a rectifier diode or signal diode is by thinking of it as resembling the line in the diode schematic symbol.
## Signal Diodes
 Also known as switching diodes and high-speed diodes, their small size provides a low junction capacitance, enabling fast response times. They are not designed to withstand high currents. Signal diodes traditionally were packaged with axial leads for through-hole installation (like traditional-style resistors). Although this format still exists, signal diodes are now more commonly available in surface-mount formats.
## Zener Diode
The Zener is intended to be reverse-biased; that is, conventional current is applied through it “in the wrong direction” compared with conventional diodes. As the current increases, the dynamic resistance of the Zener diode decreases.
![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_21h22m.png)

## Transient Voltage Suppressor (TVS)
 A form of Zener diode designed to protect sensitive devices from transient voltage spikes by clamping them—in other words, diverting the energy to ground. A TVS can absorb as much as 30,000 volts from a lightning strike or static discharge. Typically the Zener diode is incorporated in a network of other diodes in a surface-mount integrated circuit chip. Zener diodes can also be used in circuits to handle electrostatic discharge (ESD), which can occur when a person unknowingly accumulates an electrostatic potential and then grounds it by touching an electronic device.

## Varactor Diode
 Also known as a varicap, this type of diode has variable capacitance controlled by reverse voltage. While other diodes may exhibit this same phenomenon, the varactor is specifically designed to exploit it at very high frequencies. The voltage expands or contracts the depletion region in the junction between the P and N regions, which can be thought of as analogous to moving the plates of a capacitor nearer together or farther apart.
In almost all radio, cellular, and wireless receivers, a varactor controls a phase-locked loop oscillator. In ham radio receivers, it can be used to adjust the tuning of a filter that tracks an incoming radio frequency.
A varactor is always reverse-biased below its breakdown voltage, so that there is no direct conduction.
## Tunnel Diode, Gunn Diode, PIN Diode
 Mostly used in very high frequency or microwave applications, where ordinary diodes are unacceptable because they have insufficiently high switching speeds.

## Application

##Voltage Selection 
A diode is sensitive to the relative voltage between its anode and cathode terminals. In other words, if the cathode is at 9V relative to the ground in the circuit, and the anode is at 12V, the 3V difference will easily exceed the threshold voltage, and the diode will pass current. (Actual tolerable values will depend on the forward voltage capability of the diode.) If the voltages are reversed, the diode will block the current.
This attribute can be used to make a device choose automatically between an AC adapter and a 9V battery. The schematic is shown in Figure 26-16. When an AC adapter that delivers 12VDC is plugged into a wall outlet, the adapter competes with the battery to provide power to a voltage regulator. The battery delivers 9VDC through the lower diode to the cathode side of the upper diode, but the AC adapter trumps it with 12VDC through the upper diode. Consequently, the battery ceases to power the circuit until the AC adapter is unplugged, at which point the battery takes over, and the upper diode now prevents the battery from trying to pass any current back through the AC adapter.
![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_21h33m.png)

##Voltage Clamping 
A diode can be used to clamp a voltage to a desired value. If an input to a 5V CMOS semiconductor or similarly sensitive device must be prevented from rising out of range, the anode of a diode can be connected to the input and the cathode to a 5V voltage source. If the input rises much above 5.6V, the potential difference exceeds the diode’s junction threshold, and the diode diverts the excess energy.

![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_21h40m.png)

if two or more outputs from a logic chip or microcontroller are intended to drive, or share, another device such as a single LED, as shown in Figure 26-18. In this role, the diodes wired in parallel behave similarly to an OR gate, while preventing either output from the chip from feeding current back into the other output.


![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_21h42m.png)

##DC Voltage Regulation and Noise Suppression
 As previously noted, the dynamic resistance of a reverse-biased Zener diode will diminish as the current increases. This relationship begins at the point where breakdown in the diode begins—at its Zener voltage--and is approximately linear over a limited range. The unique behavior of the Zener makes it usable as a very simple voltage controller when placed in series with a resistor as shown in Figure 26-19. It is helpful to imagine the diode and the resistor as forming a kind of voltage divider, with power being taken out at point A in the schematic. If a supply fluctuation increases the input voltage, this will tend to increase the current flowing through the Zener, and its dynamic resistance will diminish accordingly. A lower resistance in its position in the voltage divider will reduce the output voltage at point A, thus tending to compensate for the surge in input voltage.

Conversely, if the load in the circuit increases, and tends to pull down the input voltage, the current flowing through the Zener will diminish, and the voltage at point A will tend to increase, once again compensating for the fluctuation in the circuit.
As the series resistor would be a source of heat, a transistor could be added to drive the load, as shown in Figure 26-20.
![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_21h49m.png)

##AC Voltage Control and Signal Clipping 
A more practical Zener application would be to limit AC voltage and/or impose clipping on an AC sinewave, using two diodes wired in series with opposed polarities. The basic schematic is shown in Figure 26-21, while clipping of the AC sinewave is illustrated in Figure 26-22. In this application, when one diode is reverse-biased, the other is forward-biased. A forward-biased Zener diode works like any other diode: it allows current to pass relatively freely, so long as the voltage exceeds its threshold. When the AC current reverses, the Zeners trade their functions, so that the first one merely passes current while the second one limits the voltage. Thus, the diodes divert peak voltage away from the load. The Zener voltage of each diode would be chosen to be a small margin above the AC voltage for voltage control, and below the AC voltage for signal clipping.

![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_21h51m.png)

## Voltage Sensing
A Zener diode can be used to sense a small shift in voltage and provide a switched output in response.
In Figure 26-23, the upper schematic shows a Zener diode preventing voltage from reaching the emitter of a PNP transistor while the divided input signal is below the Zener (breakdown) voltage of the diode. In this mode, the transistor is relatively non-conductive, very little current flows through it, and the output is now at nearzero voltage. As soon as the input signal rises above the Zener voltage, the transistor switches on and power is supplied to the output. The input is thus replicated in the output, as shown in the upper portion of Figure 26-24. In Figure 26-23, the lower schematic shows a Zener diode preventing voltage from reaching the base of an NPN transistor while the input signal is below the Zener (breakdown) voltage of the diode. In this mode, the transistor is relatively non-conductive, and power is supplied to the output. As soon as the input signal rises above

![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_22h01m.png)

![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_22h02m.png)

##Wrong Type of Diode
 If a Zener diode is used accidentally where a signal or rectifier diode is appropriate, the circuit will malfunction, as the Zener will probably have a much lower breakdown voltage, and therefore will not block reverse current. Conversely, if a signal or rectifier diode is used where the circuit calls for a Zener diode, reverse voltage will be clamped (or regulated at the diode’s forward voltage value). Since diodes are often poorly marked, a sensible precaution is to store Zener diodes separately from all other types.

# Unijunction Transistor

Despite their names, the unijunction transistor (UJT) and programmable unijunction transistor (PUT) are not current-amplification devices like bipolar transistors. They are switching components that are more similar to diodes than to transistors.
The UJT declined in popularity during the 1980s after introduction of components such as the 555 timer, which offered more flexibility and a more stable output frequency, eventually at a competitive price
Whereas an integrated circuit such as a 555 timer generates a square wave, unijunction transistors in oscillator circuits generate a series of voltage spikes.
The PUT is often used to trigger a thyristor (described in Volume 2) and has applications in lowpower circuits, where it can draw as little as a few microamps.
Schematic symbols for the two components are shown in Figure 27-1 and Figure 27-2. Although the symbol for the UJT is very similar to the symbol for a field-effect transistor (FET), its behavior is quite different. The bent arrow identifies the UJT, while a straight arrow identifies the FET. This difference is of significant importance.
![](file:///C:/Users/f126ck/Desktop/markEd/29October2019_22h06m.png)
