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

<img src="images/04October2019_17h06m.png" style="zoom: 33%;" />

## Toggle Switch
<img src="images/04October2019_17h10m.png" style="zoom: 33%;" />


## SIP & DIP
<img src="images/04October2019_17h15m.png" style="zoom: 33%;" /> <img src="images/04October2019_17h15xcm.png" style="zoom: 33%;" />

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
<img src="images/04October2019_17h24m.png" style="zoom: 39%;" />

## Deviatore



<img src="images/04October2019_17h30m.png" style="zoom: 33%;" />

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
<img src="images/04October2019_17h43m.png" style="zoom: 25%;" />

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
<img src="images/04October2019_18h20m.png" style="zoom:50%;" />
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

<img src="images/04October2019_19h09m.png" style="zoom:50%;" />

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

<img src="images/04October2019_19h39m.png" style="zoom:50%;" />

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
<img src="images/05October2019_17h09m.png" style="zoom:50%;" />
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
<img src="images/05October2019_17h25m.png" style="zoom:50%;" />
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
<img src="images/06October2019_18h24m.png" style="zoom:50%;" />
The key to the efficiency of a DC-DC converter is an inductor, which stores energy in its magnetic field during “on” pulse and releases it in the discharge phase. Thus, the inductor is used as a temporary reservoir and minimizes the ripple current. All converter variants use a coil for this purpose, although its placement varies in relation to the diode and capacitor that complete the basic circuit.
variable D is the duty cycle in the pulse train generated through an internal MOSFET switch. The duty cycle is the fraction of the total on-off cycle that is occupied by each “on” pulse. In other words, if
Ton is the duration of an “on” pulse and Toff is the “off” time: 
D = Ton / ( Ton + Toff )
##Buck Converter
 See Figure 17-3. The output voltage is lower than the input voltage. The input and output share a common ground. For this circuit: 
Vout = Vin * D
<img src="images/06October2019_18h28m.png" style="zoom:50%;" />

## Boost Converter
 See Figure 17-4. The output voltage is greater than the input voltage. The input and output share a common ground. For this circuit: 
Vout = Vin / (1-D)
<img src="images/06October2019_18h29m.png" style="zoom:50%;" />

## Flyback Converter with Inductor
Commonly known as a *buck-boost converter*. See Figure 17-5. The output voltage can be less than or greater than the input voltage. The input and output share a common ground. For this circuit:
Vout = Vin * ( D / ( 1 - D) )
<img src="images/06October2019_18h31m.png" style="zoom:50%;" />

## Flyback Converter with Transformer 
See Figure 17-6. The output voltage can be less than or greater than the input voltage. The input and output are isolated from one another. For this circuit:
Vout = Vin * ( D / ( 1 - D) )
<img src="images/06October2019_18h32m.png" style="zoom:50%;" />
Using a transformer in the converter allows multiple outputs with different voltages, supplied through multiple transformer windings.
On a circuit board that is primarily populated with 5VDC components and is fed by a single 5VDC power supply, a converter can be used to supply 12VDC for one special purpose, such as an analog-digital converter or a serial data connection.

# DC-AC inverter
he inverter receives an input of direct current (typically 12VDC from a car battery) and delivers an output of alternating current (AC) in the range 110VAC-120VAC or 220VAC-240VAC, suitable to power many lowwattage appliances and devices.
The first stage of an inverter typically raises a 12VDC input to a higher DC voltage via an internal DC-DC converter, then uses a switching circuit to create an approximation of the sinusoidal profile that is characteristic of AC voltage.
The RMS value is important as a means to calculate actual power delivered because it can be multiplied by the current to obtain an approximate value in watts.
<img src="images/06October2019_18h46m.png" style="zoom:50%;" />
As a first step toward a better approximation of a sine wave, gaps of zero voltage can be inserted between square-wave pulses. This “gapped” square wave is shown in Figure 18-3.
<img src="images/06October2019_18h47m.png" style="zoom:50%;" />

# Voltage Regulator
A linear voltage regulator provides a tightly controlled DC output, which it derives from an unregulated or poorly regulated DC input. The DC output remains constant regardless of the load on the regulator (within specified limits). It is a cheap, simple, and extremely robust.
Some voltage regulators include an extra pin, typically known as an enable pin, which switches off the device in response to a signal from a microcontroller or logic gate. Some regulators offer another option, an additional status pin that can signal a microcontroller that an error mode exists if the regulator output falls significantly below its rated value.
A linear voltage regulator cannot respond instantly to changes in input voltage. Therefore, if the input supply contains voltage spikes, these spikes may pass through the regulator. Bypass capacitors should be applied preventively. component.
All linear regulators function by taking some feedback from the output, deriving an error value by comparing the output with a reference voltage (most simply provided by a zener diode), 
and using the error value to control the base of a pass transistor that is placed between the input and the output of the regulator. Because the transistor operates below saturation level, its output current varies linearly with the current applied to its base, and this behavior gives the linear regulator is name.
The voltage difference required between the base and emitter of an NPN transistor is a minimum of 0.6V. Because multiple transistors are used inside a standard-type voltage regulator, it requires a minimum total voltage difference, between its input and its output, of 2VDC. This voltage difference is known as the dropout voltage. If the voltage difference falls below this minimum, the regulator ceases to deliver a reliable output voltage until the input voltage rises again. Low dropout regulators allow a lower voltage difference, but are more expensive and less commonly used.
<img src="images/06October2019_20h05m.png" style="zoom:50%;" />

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
<img src="images/27October2019_12h38m.png" style="zoom:50%;" />
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
<img src="images/27October2019_19h35m.png" style="zoom:50%;" />
Inside a servo motor’s casing, the electronics include a potentiometer that turns with the output shaft, to provide feedback confirming the motor’s position. The limited turning range of the potentiometer determines the turn limits of the motor output shaft.
Karbonite gears are a reinforced plastic composite material used in Hitec RC servos that show almost five times the strength of nylon gears and better wear resistance. Cycle times of over 300,000 have been observed with these gear trains showing virtually no wear. Karbonite-geared servos are more expensive than those using nylon ones but are highly durable.[1] Hobbyists are advised avoid use of thread locking compounds on Karbonite as this will cause the plastic to fail. 
So-called **digital servos** use faster internal electronics than the older, so-called analog servos, and because they sample the incoming pulse stream at a higher frequency, they are more responsive to small, rapid commands from the controller. For this reason they are preferred by hobbyists using servos to control the flight of model airplanes.
A servo generally has three wires, colored red (power supply), black or brown (ground), and orange, yellow, or white (for the pulse train from the controller). The ground wire to the motor must be common with the ground of the controller, and consequently a ceramic bypass capacitor of 0.1μF or 0.01μF should be placed between the (red) power wire to the motor and ground. A protection diode should also be used.
Various shaft attachments are available from the same online hobby-electronics suppliers that sell servos. The attachments include discs, single arms, double arms, and four arms in a crossshaped configuration. A single-arm attachment is often known as a horn, and this term may be applied loosely to any kind of attachment.
<img src="images/27October2019_19h47m.png" style="zoom:33%;" />

## Modification for Continuous Rotation
 It is possible to modify a small servo motor so that it will rotate continuously. First the motor case must be opened, and the potentiometer must be centered by using a controller to send some 1.5ms pulses. The potentiometer must then be glued or otherwise secured with its wiper in this precise center position, after which the potentiometer is disconnected from the drive train.
Mechanical stops that would limit the rotation of the motor shaft must be cut away, after which the motor is reassembled. Because the potentiometer has been immobilized, the motor’s internal electronics will now “see” the shaft as being in its center position at all times. If the controller sends a pulse instructing the motor to seek a position clockwise or counter-clockwise from center, the motor will rotate in an effort to reach that position. Because the potentiometer will not provide feedback to signal that the motor has achieved its goal, the shaft will continue to rotate indefinitely.

**The purpose of modifying a servo for continuous rotation is to take advantage of its high torque, small size, light weight, and the ease of controlling it with a microcontroller.**
##Permanent Magnet Stepper Motors 
More commonly, the rotor of a stepper motor contains permanent magnets, which require the controller to be capable of reversing the magnetic field created by each of the stator coils, so that they alternately attract and repel the rotor magnets.
In a bipolar motor, the magnetic field generated by a coil is reversed simply by reversing the current through it. This is shown diagrammatically in Figure 25-3. In a unipolar motor, the magnetic field is reversed by applying positive voltage to the center tap of a coil, and grounding one end or the other. This is shown diagrammatically in Figure 25-4.
<img src="images/27October2019_20h01m.png" style="zoom:33%;" />
<img src="images/27October2019_20h02m.png" style="zoom:33%;" />

## Bipolar Stepper Motors 
The most basic way to reverse the current in a coil is by using an H-bridge configuration of switches, as shown in Figure 25-8, where the green arrow indicates the direction of the magnetic field. In actual applications, the switches are solid-state. Integrated circuits are available containing all the necessary components to control a bipolar stepper motor.
## Unipolar Motors 
The control electronics for a unipolar motor can be simpler than those for a bipolar motor, as offthe-shelf switching transistors can ground one end of the coil or the other. The classic five-wire unipolar stepper motor, often sold to hobbyists and used in robotics projects and similar applications, can be driven by nothing more elaborate than a set of 555 timer chips.
However, this type of motor is less powerful for its size and weight because only half of each coil is energized at a time.

![](images/28October2019_22h29m.png)

##Multiphase
 In a multiphase motor, multiple stator coils are usually connected in series, with a center tap applied between each pair.
<img src="images/28October2019_22h50m.png" style="zoom:50%;" />
The way in which the motor is wired enables only one stator coil to be unpowered during any step, because its two ends are at equal potential. Therefore this type of motor is capable of high torque in a relatively small format.
##Voltage Control 
Rapid stepping of a motor requires rapid creation and collapse of magnetic fields in the stator windings. Therefore, self-inductance of the windings can limit the motor speed. One way to overcome this is to use a higher voltage. A more sophisticated solution is to use a controller that provides a high initial voltage, which is reduced or briefly interrupted when a sensor indicates that coil current has increased sufficiently to overcome the self-inductance of the windings and has reached its imposed limit. This type of controller may be referred to as a chopper drive as the voltage is “chopped,” usually by power transistors. It is a form of pulse width modulation.

<img src="images/28October2019_22h57m.png" style="zoom:50%;" />

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
<img src="images/29October2019_21h22m.png" style="zoom:33%;" />

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
<img src="images/29October2019_21h33m.png" style="zoom:33%;" />

##Voltage Clamping 
A diode can be used to clamp a voltage to a desired value. If an input to a 5V CMOS semiconductor or similarly sensitive device must be prevented from rising out of range, the anode of a diode can be connected to the input and the cathode to a 5V voltage source. If the input rises much above 5.6V, the potential difference exceeds the diode’s junction threshold, and the diode diverts the excess energy.

<img src="images/29October2019_21h40m.png" style="zoom:33%;" />

if two or more outputs from a logic chip or microcontroller are intended to drive, or share, another device such as a single LED, as shown in Figure 26-18. In this role, the diodes wired in parallel behave similarly to an OR gate, while preventing either output from the chip from feeding current back into the other output.

<img src="images/29October2019_21h42m.png" style="zoom:33%;" />

##DC Voltage Regulation and Noise Suppression
 As previously noted, the dynamic resistance of a reverse-biased Zener diode will diminish as the current increases. This relationship begins at the point where breakdown in the diode begins—at its Zener voltage--and is approximately linear over a limited range. The unique behavior of the Zener makes it usable as a very simple voltage controller when placed in series with a resistor as shown in Figure 26-19. It is helpful to imagine the diode and the resistor as forming a kind of voltage divider, with power being taken out at point A in the schematic. If a supply fluctuation increases the input voltage, this will tend to increase the current flowing through the Zener, and its dynamic resistance will diminish accordingly. A lower resistance in its position in the voltage divider will reduce the output voltage at point A, thus tending to compensate for the surge in input voltage.

Conversely, if the load in the circuit increases, and tends to pull down the input voltage, the current flowing through the Zener will diminish, and the voltage at point A will tend to increase, once again compensating for the fluctuation in the circuit.
As the series resistor would be a source of heat, a transistor could be added to drive the load, as shown in Figure 26-20.
<img src="images/29October2019_21h49m.png" style="zoom:33%;" />

##AC Voltage Control and Signal Clipping 
A more practical Zener application would be to limit AC voltage and/or impose clipping on an AC sinewave, using two diodes wired in series with opposed polarities. The basic schematic is shown in Figure 26-21, while clipping of the AC sinewave is illustrated in Figure 26-22. In this application, when one diode is reverse-biased, the other is forward-biased. A forward-biased Zener diode works like any other diode: it allows current to pass relatively freely, so long as the voltage exceeds its threshold. When the AC current reverses, the Zeners trade their functions, so that the first one merely passes current while the second one limits the voltage. Thus, the diodes divert peak voltage away from the load. The Zener voltage of each diode would be chosen to be a small margin above the AC voltage for voltage control, and below the AC voltage for signal clipping.

<img src="images/29October2019_21h51m.png" style="zoom:33%;" />

## Voltage Sensing
A Zener diode can be used to sense a small shift in voltage and provide a switched output in response.
In Figure 26-23, the upper schematic shows a Zener diode preventing voltage from reaching the emitter of a PNP transistor while the divided input signal is below the Zener (breakdown) voltage of the diode. In this mode, the transistor is relatively non-conductive, very little current flows through it, and the output is now at nearzero voltage. As soon as the input signal rises above the Zener voltage, the transistor switches on and power is supplied to the output. The input is thus replicated in the output, as shown in the upper portion of Figure 26-24. In Figure 26-23, the lower schematic shows a Zener diode preventing voltage from reaching the base of an NPN transistor while the input signal is below the Zener (breakdown) voltage of the diode. In this mode, the transistor is relatively non-conductive, and power is supplied to the output. As soon as the input signal rises above

<img src="images/29October2019_22h01m.png" style="zoom:33%;" />

<img src="images/29October2019_22h02m.png" style="zoom:33%;" />

##Wrong Type of Diode
 If a Zener diode is used accidentally where a signal or rectifier diode is appropriate, the circuit will malfunction, as the Zener will probably have a much lower breakdown voltage, and therefore will not block reverse current. Conversely, if a signal or rectifier diode is used where the circuit calls for a Zener diode, reverse voltage will be clamped (or regulated at the diode’s forward voltage value). Since diodes are often poorly marked, a sensible precaution is to store Zener diodes separately from all other types.

# Unijunction Transistor

Despite their names, the unijunction transistor (UJT) and programmable unijunction transistor (PUT) are not current-amplification devices like bipolar transistors. They are switching components that are more similar to diodes than to transistors.
The UJT declined in popularity during the 1980s after introduction of components such as the 555 timer, which offered more flexibility and a more stable output frequency, eventually at a competitive price
Whereas an integrated circuit such as a 555 timer generates a square wave, unijunction transistors in oscillator circuits generate a series of voltage spikes.
The PUT is often used to trigger a thyristor (described in Volume 2) and has applications in lowpower circuits, where it can draw as little as a few microamps.
Schematic symbols for the two components are shown in Figure 27-1 and Figure 27-2. Although the symbol for the UJT is very similar to the symbol for a field-effect transistor (FET), its behavior is quite different. The bent arrow identifies the UJT, while a straight arrow identifies the FET. This difference is of significant importance.
<img src="images/29October2019_22h06m.png" style="zoom:33%;" />

The UJT is a three-terminal semiconductor device, but contains only two sections sharing a single junction—hence its name. Leads attached to opposite ends of a single channel of N-type semiconductor are referred to as base 1 and base 2, with base 2 requiring a slightly higher potential than base 1. A smaller P-type insert, midway between base 1 and base 2, is known as the emitter.
When no voltage is applied to the emitter, a relatively high resistance (usually more than 5K) prevents significant current flow from base 2 to base 1. When the positive potential at the emitter increases to a triggering voltage (similar to the junction threshold voltage of a forward-biased diode), the internal resistance of the UJT drops very rapidly, allowing current to enter the component via both the emitter and base 2, exiting at base 1. (The term “current” refers, here, to conventional current; electron flow is opposite.) Current flowing from base 2 to base 1 is significantly greater than current flowing from the emitter to base 1.
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/29October2019_22h40m.png" style="zoom:50%;" />

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/01November2019_11h30m.png" style="zoom:33%;" />

A PUT behaves similarly in many ways to a UJT but is internally quite different, consisting of four semiconducting layers and functioning similarly to a thyristor

The PUT is triggered by increasing the voltage on the anode
This component is triggered when the voltage at its anode exceeds a threshold level, while the gate sets the threshold where this occurs

This behavior is almost identical to that of a forward-biased diode, except that the threshold level can be controlled, or “programmed,” according to the value of the positive potential applied at the gate, with R1 and R2 establishing that potential by functioning as a voltage divider.

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/01November2019_11h33m.png" style="zoom:50%;" />

The triggering voltage of a UJT can be calculated from the values of R1 and R2 in Figure 27-7 and the voltage at base 1. The term Rbb is often used to represent the sum of R1 + R2, with Vbb representing the total voltage across the two resistors (this is the same as the supply voltage in Figure 27-6). Vt, the triggering voltage, is given by:
Vt = Vbb * (  R1 / Rbb )

**A programmable unijunction transistor (PUT) is sometimes referred to simply as a “unijunction transistor” (UJT). Bearing in mind the totally different modes of operation of UJT and PUT, the PUT should always be identified by its acronym or by its full name. A circuit will not function if a UJT is substituted for a PUT, or a PUT is substituted for a UJT. **

Incorrect Bias
Neither the UJT nor the PUT is designed to operate with reverse bias. In the UJT, a small forward bias should be applied from base 2 to base 1 (that is, base 2 should be at a higher potential relative to base 1) regardless of the voltage on the emitter. The emitter voltage may vary from 0 volts upward. The PUT must be forward biased between its anode and cathode (the anode must have a higher potential relative to the cathode), with an intermediate positive voltage at the gate established by resistors R1 and R2 functioning as a voltage divider (see Figure 27-7). Failure to observe correct biasing will result in unpredictable behavior and possible damage to the component.

# Transistor
A bipolar NPN transistor consists of a thin central P-type layer sandwiched between two thicker Ntype layers. The three layers are referred to as collector, base, and emitter, with a wire or contact attached to each of them. When a negative charge is applied to the emitter, electrons are forced by mutual repulsion toward the central base layer. If a forward bias (positive potential) is applied to the base, electrons will tend to be attracted out through the base. However, because the base layer is so thin, the electrons are now close to the collector. If the base voltage increases, the additional energy encourages the electrons to jump into the collector, from which they will make their way to the positive current source, which can be thought of as having an even greater deficit of electrons.

**NPN transistors enable faster switching, because electrons have greater mobility than electron-holes **

Current flow for NPN and PNP transistors is illustrated in Figure 28-2. At top-left, an NPN transistor passes no current (other than a small amount of leakage) from its collector to its emitter so long as its base is held at, or near, the potential of its emitter, which in this case is tied to negative or ground. At bottom-left, the purple positive symbol indicates that the base is now being held at a relatively positive voltage, at least 0.6 volts higher than the emitter (for a silicon-based transistor). This enables electrons to move from the emitter to the collector, in the direction of the blue arrows, while the red arrows indicate the conventional concept of current flowing from positive to negative. The smaller arrows indicate a smaller flow of current. A resistor is included to protect the transistor from excessive current, and can be thought of as the load in these circuits. At top-right, a PNP transistor passes no current (other than a small amount of leakage) from its emitter to its collector so long as its base is held at, or near, the potential of the emitter, which in this case is tied to the positive power supply. At bottom-right, the purple negative symbol indicates that the base is now being held at a relatively negative voltage, at least 0.6 volts lower than the emitter. This enables electrons and current to flow as shown. Note that current flows into the base in the NPN transistor, but out from the base in the PNP transistor, to enable conductivity. In both diagrams, the resistor that would normally be included to protect the base has been omitted for the sake of simplicity.
An NPN transistor amplifies its base current only so long as the positive potential applied to the collector is greater than the potential applied to the base, and the potential at the base must be greater than the potential at the emitter by at least 0.6 volts

A voltage divider is often used to control the base potential and ensure that it remains less than the potential on the collector and greater than the potential at the emitter (in an NPN transistor)

Small signal transistors are defined as having a maximum collector current of 500 mA and maximum collector power dissipation of 1 watt. They can be used for audio amplification of low-level inputs and for switching of small currents. When determining whether a small-signal transistor can control an inductive load such as a motor or relay coil, bear in mind that the initial current surge will be greater than the rated current draw during sustained operation.

second breakdown limit. The latter refers to the tendency of a transistor to develop internal localized “hot spots” that tend to conduct more current, which makes them hotter, and able to conduct better—ultimately melting the silicon and causing a short circuit. The total power limit and the second breakdown limit reduce the safe operating area, which would otherwise be defined purely by maximum safe current and maximum safe voltage.

## Darlington
A Darlington pair of transistors may be used in this application. The overall gain of the pair can be 100,000 or more. 

In the application shown here, the microcontroller chip must share a common ground (not shown) with the transistors

The device can have its own positive supply voltage, shown here as 12VDC, but must share a common ground with the microcontroller, or with any other component which is being used on the input side.

The common-collector configuration has current gain but no voltage gain. 

**Rohm, a large semiconductor manufacturer, has included this scenario in its general information pages and concludes that the primary indicator of transposed connections is that the β value, or hFE , drops to about 1/10th of specification. If you are using a transistor that works but provides much less amplification than you expect, check that the emitter and collector leads are not transposed **

#FET
JFETs A junction field-effect transistor (or JFET) is the simplest form of FET. Just as a bipolar transistor can be of NPN or PNP type, a JFET can have an Nchannel or P-channel, depending whether the channel that transmits current through the device is negatively or positively doped.
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/01November2019_12h08m.png" style="zoom:33%;" /> 

The JFET is like a normally-closed switch. It has a low resistance so long as the gate is at the same potential as the source. However, if the potential of the gate is reduced below the potential of the source—that is, the gate acquires a more relatively negative voltage than the source—the current flow is pinched off as a result of the field created by the gate. This is suggested by the lower diagram in Figure 29-4.

A bipolar transistor tends to block current flow by default, but becomes less resistive when its base is forward-biased.
Therefore it can be referred to as an enhancement device. By contrast, an N-channel JFET allows current to flow by default, and becomes more resistive when its base is reverse-biased, which widens the depletion layer at the base junction. Consequently it can be referred to as a depletion device.
Suppose the gate of an N-channel JFET is connected with the source, so that Vgs=0. Now if Vds increases, the current flowing through the channel of the JFET also increases, approximately linearly with Vds. In other words, initially the JFET behaves like a low-value resistor in which the voltage across it, divided by the amperage flowing through it, is approximately constant. This phase of the JFET’s behavior is known as its ohmic region. While the unbiased resistance of the channel in a JFET depends on the component type, it is generally somewhere between 10Ω and 1K.

##MESFET 
The acronym stands for MEtal-Semiconductor Field Effect Transistor. This FET variant is fabricated from gallium arsenide and is used primarily in radio frequency amplification
## V-Channel MOSFET
It is able to pass the high current because its channel resistance is well under 1Ω. These devices, commonly referred to as power MOSFETs, are available from all primary semiconductor manufacturers and are commonly used in switching power supplies

## Trench MOS
 The TrenchMOS or Trenchgate MOS is a MOSFET variant that encourages current to flow vertically rather than horizontally, and includes other innovations that enable an even lower channel resistance, allowing high currents with minimal heat generation. This device is finding applications in the automobile industry as a replacement for electromechanical relays.

## Static Electricity
Because the gate of a MOSFET is insulated from the rest of the component, and functions much like a plate of a capacitor, it is especially likely to accumulate static electricity. This static charge may then discharge itself into the body of the component, destroying it.






# END BOOK 1

#START BOOK 2

#SCR
An SCR is a solid-state switch that in many instances can pass high currents at high voltages.
Like a bipolar transistor, it is triggered by voltage applied to a gate. Unlike the transistor, it allows the flow of current to continue even when the gate voltage diminishes to zero.
By comparison, the diac and triac are designed to be bidirectional.
When the SCR is activated by a positive voltage at the gate, current can now flow from anode to cathode, although it is still blocked from cathode to anode.
When the flow reaches a level known as the latching current, the flow will continue even after the triggering voltage drops to zero

This behavior causes it to be known as a regenerative device.
If the current between anode and cathode starts to diminish while the gate voltage remains zero, the current flow will continue below the latching level until it falls below the value known as the holding current. The flow now ceases. Thus, the only way to end a flow of current that has been initiated through an SCR is by reducing the flow or attempting to reverse it.
Unlike a transistor, an SCR is either “on” or “off” and does not function as a current amplifier
The fast switching response also enables an SCR to interrupt and abbreviate each positive phase of an AC waveform, to reduce the average power supplied. This is known as phase control.
**SCRs are also used to provide overvoltage protection.**
Among its applications are small-engine ignition and crowbar overvoltage protection, so named because it shorts a power supply directly to ground, much like a crowbar being dropped across the terminals of a car battery (but hopefully with a less dramatic outcome)
![](file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_10h49m.png)
### Crowbar 
A crowbar circuit is an electrical circuit used for preventing an overvoltage condition of a power supply unit from damaging the circuits attached to the power supply. It operates by putting a short circuit or low resistance path across the voltage output (Vo), quite like were one to drop a crowbar across the output terminals of the power supply. Crowbar circuits are frequently implemented using a thyristor, TRIAC, trisil or thyratron as the shorting device. Once triggered, they depend on the current-limiting circuitry of the power supply or, if that fails, the blowing of the line fuse or tripping the circuit breaker. 
An example crowbar circuit is shown to the right. This particular circuit uses an LM431 adjustable zener regulator to control the gate of the TRIAC. The resistor divider of R1 and R2 provide the reference voltage for the LM431. The divider is set so that during normal operating conditions, the voltage across R2 is slightly lower than VREF of the LM431. Since this voltage is below the minimum reference voltage of the LM431, it remains off and very little current is conducted through the LM431. If the cathode resistor is sized accordingly, very little voltage will be dropped across it and the TRIAC gate terminal will be essentially at the same potential as MT1, keeping the TRIAC off. If the supply voltage increases, the voltage across R2 will exceed VREF and the LM431 cathode will begin to draw current. The voltage at the gate terminal will be pulled down, exceeding the gate trigger voltage of the TRIAC and latching it on. 
Thus, a crowbar will not automatically return to normal operation when the overvoltage condition is removed; power must be removed entirely to stop its conduction. 
An active crowbar is a crowbar that can remove the short circuit when the transient is over thus allowing the device to resume normal operation. Active crowbars use a transistor, gate turn off (GTO) thyristor or forced commutated thyristor instead of a thyristor to short the circuit. Active crowbars are commonly used to protect the frequency converter in the rotor circuit of doubly fed generators against high voltage and current transients caused by the voltage dips in the power network. Thus the generator can ride through the fault and quickly continue the operation even during the voltage dip.
Using a transistor instead of a thyristor or triac would not be so easy, since the power supply necessary to drive the base or gate of the transistor goes away when the supply is shorted, whereas the thyristor or triac needs no further gate drive to stay on once triggered. This is the reason why thyristors and triacs are so widely used in this application.
One property of crowbar circuits that is often an advantage is that it becomes very evident that something is wrong and needs fixing once it has triggered. 

http://www.learningelectronics.net/circuits/adjustable-zener-diode_19.html

## Internal config
The function of an SCR can be imagined as being similar to that of a PNP transistor paired with an NPN transistor, as shown in Figure 1-6. In this simplified schematic, so long as zero voltage is applied to the “gate” wire, the lower (NPN) transistor remains nonconductive.

### Clamp
A clamper is an electronic circuit that fixes either the positive or the negative peak excursions of a signal to a defined value by shifting its DC value[2]. The clamper does not restrict the peak-to-peak excursion of the signal, it moves the whole signal up or down so as to place the peaks at the reference level. A diode clamp (a simple, common type) consists of a diode, which conducts electric current in only one direction and prevents the signal exceeding the reference value; and a capacitor, which provides a DC offset from the stored charge. The capacitor forms a time constant with the resistor load, which determines the range of frequencies over which the clamper will be effective. 

### Low Voltage ride through
Many generator designs use electric current flowing through windings to produce the magnetic field on which the motor or generator operates. This is in contrast to designs that use permanent magnets to generate this field instead. Such devices may have a minimum working voltage, below which the device does not work correctly, or does so at greatly reduced efficiency. Some will disconnect themselves from the circuit when these conditions apply. The effect is more pronounced in doubly-fed induction generators (DFIG)[3], which have two sets of powered magnetic windings, than in squirrel-cage induction generators which have only one. Synchronous generators may slip and become unstable, if the voltage of the stator winding goes below a certain threshold.
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_11h07m.png" style="zoom:33%;" />
Consequently, the upper (PNP) transistor cannot sink current, and this transistor also remains nonconductive.
When voltage is applied to the “gate,” the lower transistor starts to sink current from the upper transistor. This switches it on. The two transistors
now continue to conduct even if power to the “gate” is disconnected, because they have created a positive feedback loop.
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_11h09m.png" style="zoom:33%;" />

## SCR Concept Demo 
In Figure 1-9, pushbutton S1 applies voltage to the gate of the SCR, which puts the SCR in selfsustaining conductive mode. When S1 is released, the meter will show that current continues to pass between the anode and the cathode. The X0403DF SCR suggested for this circuit has a holding current of 5mA, which a 5VDC supply should be able to provide with the 1K resistor in the circuit. If necessary, this resistor can be reduced to 680Ω.
Now if pushbutton S2 is pressed, the flow is interrupted. When S2 is released, the flow will not resume. Alternatively, if pushbutton S3 is pressed while the SCR is conducting current, the flow is diverted around the SCR, and when the pushbutton is released, the flow through the SCR will not resume. Thus, the SCR can be shut down either by a normally closed pushbutton in series with it (which will interrupt the current), or a normally open pushbutton in parallel with it (which will divert the current).
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_11h14m.png" style="zoom:50%;" />

Any SCR will impose a forward voltage drop, which typically ranges from around 1V to 2V, depending on the component.
Leakage in the “off” state may be as high as 0.5mA or as low as 5µA. Gate trigger voltage is likely to range from 0.8V to 1.5V, and trigger current of 0.2mA to 15mA is typical.

Although other applications are possible, in practice SCRs have two main applications:
• Phase control, which interrupts each positive phase of an AC power supply. It can moderate the speed of a motor or the heat generated by a resistive load.
• Overvoltage protection. This can safeguard sensitive components in a circuit where there is a DC power supply.

Phase Control Phase control is a convenient way to control or limit the AC power delivered to a load by abbreviating each pulse in the AC waveform. This is done by adjusting the gate voltage so that the SCR blocks the first part of each positive phase, then conducts the remainder, and then stops conducting below its holding level. The SCR will then block the reversed flow in the negative phase of the AC waveform, but an additional SCR with opposite polarity can be added.
This is a form of pulse-width modulation.

Six SCRs may be used to control three-phase power.

**A very rapid increase in forward voltage at the anode can induce a triggering voltage in the gate by capacitive coupling. As a result, the SCR can trigger itself without any external application of gate voltage. This is sometimes known as dv/dt triggering. If necessary, a snubber circuit can be added across the anode input to prevent sudden voltage transitions. **
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_14h47m.png" style="zoom:50%;" />


# Diac
The diac is a bidirectional thyristor with only two terminals. It blocks current until it is subjected to sufficient voltage, at which point its impedance drops very rapidly. It is primarily used to trigger a triac for purposes of moderating AC power to an incandescent lamp, a resistive heating element, or an AC motor. The two leads on a diac have identical function and are interchangeable.
By comparison, a triac and an SCR are thyristors with three leads, one of them being referred to as the gate, which determines whether the component becomes conductive. A triac and a diac allow current to flow in either direction, while an SCR always blocks current in one direction.

Because its two leads are functionally identical, they do not require names to differentiate them. They are sometimes referred to as A1 and A2, in recognition that either of them may function as an anode; or they may be identified as MT1 and MT2, MT being an acronym for “main terminal.”

When only a moderate voltage is applied (usually less than 30V) the diac remains in a passive state and will block current in either direction, although a very small amount of leakage typically occurs. When the voltage exceeds a threshold known as its breakover level, current can flow, and the diac will continue to conduct until the current falls below its holding level
The diac cannot function as a switch, because it lacks the third terminal which is found in a triac, an SCR, or a bipolar transistor. However, it is well suited to drive the gate of a triac, because the behavior of a diac is symmetrical in response to opposite voltages, while the triac is not.
This is known as phase control, as it controls the phase angle at which the diac allows current to flow.
A **sidac** behaves very similarly to a diac, its name being derived from “silicon diode for alternating current.” Its primary difference from generic diacs is that it is designed to reach its breakover voltage at a higher value, typically 120VAC or 240VAC.
When performing its function to trigger a triac, a diac is unlikely to pass more than 100mA.

On a datasheet, a value for breakover current is valid only within a recommended temperature range. A buildup of heat can provoke unexpected triggering.
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_15h01m.png" style="zoom:50%;" />

## Symbol of diac
![](file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_15h02m.png)

# TRIAC
The triac is ubiquitous in AC dimmers for incandescent lamps. It is also used to control the speed of AC motors and the output of resistive heating elements. It is a type of thyristor which contains five segments of p-type and n-type silicon and has three leads, one of them attached to a gate that can switch a bidirectional flow of current between the other two. Its name was originally a trademark, generally thought to be derived from the phrase “triode for AC.”
**An SCR (silicon-controlled rectifier) is a thyristor that resembles a triac, as it has three leads, one of them a gate. However, it only allows current to flow in one direction.**

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_17h01m.png" style="zoom:50%;" />

The A1 terminal (or T1, or MT1) is always shown closer to the gate than A2 (or T2, or MT2). This distinction is important because although the triac can pass current in either direction, its behavior is somewhat asymmetrical.
When no gate voltage is applied, the triac remains in a passive state and will block current in either direction between A1 and A2, although a very small amount of leakage typically occurs. If the gate potential becomes sufficiently positive or negative relative to terminal A1, current can begin to flow between A1 and A2 in either direction. This makes the triac ideal for controlling AC.

Quadrants While a gate voltage is applied, four operating modes are possible. In each case, A1 is the reference (which can be thought of as being held at a neutral ground value). Because the triac is conducting AC, voltages above and below ground will occur. The four modes of operation are often referred to as four quadrants, and are typically arranged as shown in Figure 3-6.
n this encyclopedia, current is always shown flowing from a more-positive location to a more-negative location. Quadrant 1 (upper right) A2 is more positive than A1, and the gate is more positive than A1. Conventional current (positive to negative) will flow from A2 to A1. (This behavior is very similar to that of an SCR.)
Quadrant 2 (upper left) A2 is more positive than A1, and the gate is more negative than A1. Once again, conventional current (positive to negative) will flow from A2 to A1.

Quadrant 3 (lower left) A2 is more negative than A1, and the gate is more negative than A1. Conventional current is reversed from A1 to A2.
Quadrant 4 (lower right) A2 is more negative than A1, but the gate is more positive than A1. Conventional current is reversed from A1 to A2.

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_17h06m.png" style="zoom:50%;" />

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_17h09m.png" style="zoom:50%;" />

##Breakover Voltage 
If a much higher voltage is applied to A2, the triac can be forced to conduct current without any triggering voltage being applied to the gate. This occurs when the potential between A1 and A2 reaches the triac’s breakover voltage, although the component is not designed to be used this way. The concept is illustrated in Figure 3-10, which can be compared with the behavior of an SCR illustrated in Figure 1-8 and the behavior of a diac shown in Figure 2-5. While the term breakdown voltage defines the minimum reverse voltage required to force a diode to conduct, breakover voltage refers to the minimum forward voltage that has this effect. Because a triac is designed to conduct in both directions, it can be thought of as having a breakover voltage in both directions.

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_17h14m.png" style="zoom:50%;" />

## Triac Triggered by a Diac 
The problem of asymmetrical triggering can be overcome if the triac is triggered with a voltage pulse generated by another component that does behave symmetrically. The other component is almost always a diac, which is another type of thyristor. Unlike an SCR or a triac, it has no gate. It is designed to be pushed beyond its breakover voltage, at which point it latches and will continue to conduct until current flowing through it diminishes below its holding level. 

This emits a switching signal to a triac only when the AC voltage passes through zero. A zero cross circuit is desirable because it creates much less interference. The use of an optocoupler helps to isolate the triac from other components.(((“zero cross circuit”))

##Charge Storage 
While switching AC, the internal charge between A1 and A2 inside the triac requires time to dissipate before the reverse voltage is applied; otherwise, charge storage occurs, and the component may start to conduct continuously. For this reason, the triac is normally restricted to relatively low frequencies such as domestic 60Hz AC power.
In a datasheet, the term commutating dv/dt defines the rate of rise of opposite polarity voltage that the triac can withstand without locking into a continuous-on state.
An RC snubber network is often wired in parallel with A1 and A2 to control the rise time of voltage to the triac

An RC snubber network is often wired in parallel with A1 and A2 to control the rise time of voltage to the triac

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_17h25m.png" style="zoom:50%;" />

Low-Temperature Effects Significantly higher gate current will be required by a triac operating at low temperatures

a triac will tend to suffer from charge storage if there is insufficient time between the end of one half-cycle and the beginning of the next. A component that works with a resistive load may cease to function if it is used, instead, to power an inductive load.

# Solid State Relay

SSR
Very fast response, typically 1µs on and 0.5µs off.
Very low power consumption on the input side, as low as 5mA at 5VDC. Many solid-state relays can be driven directly from logic chips
No contact bounce; a clean output signal
No coil that would introduce back EMF into the circuit
Passes some leakage current (usually measured in microamps) on the output side when the relay is supposed to be “off.”
The MOSFETs require so little power, it can be provided entirely by light falling on an array of 20 or more photodiodes inside the SSR package.
A zero crossing SSR is one that (a) switches AC current and (b) will not switch “on” until the instant when the AC voltage crosses through 0V. The advantages of this type are that it does not have to be built to switch such a high current, and creates minimal voltage spike when the switching occurs.

Solid-state relays are SPST devices, but different models may have a normally closed or normally open output. If you require double-throw operation, two relays can be combined, one normally closed, the other normally open. See Figure 4-4.
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/02November2019_17h36m.png" style="zoom:50%;" />

Overheating Caused by Changing Duty Cycle

## Low Voltage Output Current May Not Work  
To test a solid-state relay, apply actual voltages on input and output sides and use a load such as an incandescent light bulb. Merely applying a meter on the output side, set to measure continuity, may not provide sufficient voltage to enable the relay to function, creating the erroneous impression that it has failed.
##I nability to Measure AC Output
 When a multimeter is used to test continuity across the output of an AC-switching solid-state relay of zero-crossing specification, the meter will generate enough voltage to prevent the solid-state relay from finding zero voltage across its output terminals, and consequently the solidstate relay won’t switch its output.
## Relay Turns On but Won’t Turn Off
 When a solid-state relay controls a relatively high-impedance load such as a small solenoid (see Volume 1) or a neon bulb (see Chapter 19), the relay may switch the device on but will seem unable to switch it off. This is because the leakage current of the solid-state relay, in its “off” state,
may be just enough to maintain the load in its “on” state.

## Relays in Parallel Won’t Work 
Two solid-state relays usually cannot be used in parallel to switch twice as much current. Because of small manufacturing variances, one relay will switch on a moment before the other. When the first relay is on, it will divert the load current away from the second relay. The second relay needs a small amount of current on its output side, to function. Without any current, it will not switch on. This means the first relay will pass the total current without any help from the second relay, and will probably burn out, while the second relay does nothing.

## Output Device Doesn’t Run at Full Power
 A solid-state relay imposes a voltage reduction on its output side. This will be a fixed amount, not a percentage. When switching 110V, this difference may be negligible; when switching 12V, it may deliver only 10.5V, which represents enough of a drop to cause a motor or a pump to run noticeably more slowly. 

## Solid-State Relays and Safety
 Disconnects Because a solid-state relay always allows some leakage in its “off” state, it can still deliver a shock when used to switch high voltages. For this reason, it may not be suitable in a safety disconnect.

# Optocoupler

The output from a logic chip passes through an optocoupler to an inductive load such as a relay coil, which may create voltage spikes that would be hazardous to the chip.

The noisy signal from an electromagnetic switch passes through an optocoupler to the input of a logic chip.

The low-voltage output from a sensing device on a human patient passes through an optocoupler to some medical equipment, such as an EEG machine, where higher voltages are used.

The low-voltage output from a sensing device on a human patient passes through an optocoupler to some medical equipment, such as an EEG machine, where higher voltages are used.

Optocouplers also eliminate ground loops, which tend to be induced by small differences in ground potential, introducing hum or buzz in audio applications when two or more power supplies are tied together.
The type of optocoupler that contains a photoresistor and is commonly used by musicians was initially trademarked as a Vactrol, and that term is still used generically. Vactrols have also been used to provide audio compression in telephone voice networks, and were used in photocopiers and photographic exposure meters, but these applications are now obsolete.
A PIN diode can respond in less than a nanosecond; its acronym is derived from its fabrication from p-type and n-type semiconductor layers with an intrinsic layer connecting them. . This additional layer can be responsive to light. When the diode is slightly reverse-biased, a photon entering the intrinsic layer can dislodge an electron, enabling current to flow. The reverse bias enlarges the active area and enhances the effect. In this mode, the PIN acts like a photoresistor, appearing to reduce its resistance in response to light.

The LED in an optocoupler typically requires 5mA at a forward voltage of 1.5V to 1.6V.

The primary purpose of an optocoupler is to provide protection against excessive voltage—from transients, incompatible power supplies, or equipment with unknown characteristics. 
**If a device is designed to be plugged into a USB port on a computer, for instance, the computer may be isolated via an optocoupler.**
While significant overload will cause immediate burnout, slightly exceeding the current rating of the LED may have more pernicious consequences, as the LED may not fail until days or weeks have passed without any sign of trouble. The failure of the optocoupler will be unexpected and difficult to determine.

# Comparator
A comparator is an integrated circuit chip that compares a variable voltage on one input pin with a fixed, reference voltage on a second input pin. Depending which voltage is higher, the output from the comparator will be high or low.

f positive feedback is added through external resistors, hysteresis can be introduced. We may imagine a hysteresis zone extending above and below the reference voltage level.

This is a small voltage, in addition to the reference voltage, which the comparator will require to toggle its output in either direction, up or down.
Vio sets the limit of resolution of the comparator, which will not respond unless the input voltage exceeds the reference voltage by this amount
Common values for VIO range from 1mV to 15mV.
Because the comparator will not respond until the reference voltage is exceeded by VIO, the output pulse width will be narrower than if the comparator reacted at the point where the variable voltage input was precisely the same as the reference voltage.

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/03November2019_11h52m.png" style="zoom:50%;" />

Isink is the recommended typical or maximum sink current that the component will tolerate, if it has an open-collector output.
The propagation delay in a comparator is measured from the moment when an input (usually a square wave) reaches the triggering value, to the time when the consequent output reaches 50% of its final value.

a typical value for a pullup resistor is 100K. 
respond with jitter when the input signal is very close to the reference voltage, because of tiny variations in heat, current, and other variables. This jitter will cause significant problems if the comparator is driving a device such as a relay, directly or indirectly.
Also, if a comparator is being used as a thermostat, to switch a heating system on and off, we do not want the comparator to respond as soon as the temperature rises just a small amount. The heating system should run for a while before it elevates the temperature beyond the hysteresis zone.

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/03November2019_12h01m.png" style="zoom:50%;" />

#Various connections

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/03November2019_12h03m.png" style="zoom:33%;" />

Differences from an Op-Amp Saturation versus linearity The output of a comparator is optimized for saturation (high or low, without intermediate levels, using positive feedback). The output of an op-amp is optimized for linearity (faithful reproduction of nuances in the input, using negative feedback).

Output mode The majority of comparators have opencollector outputs (or open-drain outputs in CMOS devices) where the voltage is established by a pullup resistor. This can be adjusted for compatibility with other components, especially 5VDC logic. Only a minority have push-pull amplifier outputs that require no pullup resistor. By comparison, among op-amps, a push-pull output that functions as a voltage source is the traditional default.

Some comparators have a push-pull output, capable of supplying output current (usually a small amount). In these instances, no pullup resistor is necessary or desirable. The output voltage range will be closest to rail-to-rail values

he advantage of an open collector (or open drain) relative to a push-pull output is that it allows the output voltage to be set independently of the power supply voltage. Another advantage is that multiple outputs can be connected in parallel, as in a window comparator circuit

## AND gate
 A set of open-collector comparators can function jointly as an AND gate, when their outputs are tied together with one pullup resistor. So long as all the output transistors are nonconductive, the output will be high. If just one comparator toggles into conductive mode, the output will be low. 

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/03November2019_12h07m.png" style="zoom:33%;" />

Bistable Multivibrator If positive feedback to the noninverting input of the comparator is sufficiently high, a voltage almost at 0V ground will be required to counter the high output from the comparator—after which, a voltage almost equal to the supply voltage will be needed to turn it back on. In other words, the comparator is behaving like a bistable multivibrator, or flip-flop.

#Relaxation Oscillator
A relaxation oscillator, which is a form of astable multivibrator, can be created using direct positive feedback in combination with delayed negative feedback.
. In Figure 6-12, positive feedback goes to the noninverting input, as before, but negative feedback also passes through a 220K resistor to the inverting input of the comparator. A 0.47µF capacitor initially holds the inverting input low, while the capacitor charges. Gradually the capacitor reaches and exceeds the charge on the noninverting input, so the output from the comparator toggles to its low state. This means that its internal transistor is now sinking current, and it discharges the capacitor. Because the noninverting input is being held at a voltage midway between supply and ground by the two 100K resistors forming a voltage divider, eventually the voltage on the inverting input controlled by the capacitor falls below the noninverting voltage, so the cycle begins again
<img src="file:///C:/Users/f126ck/Desktop/markEd/images/20191103_03November2019_12h41m.png" style="zoom:50%;" />

##Level Shifter 
Where a comparator is used simply to change the level of an input voltage, it can be referred to as a level shifter. An example of a level shifter is shown in Figure 6-13, in which a high/low 3VDC logic input is converted to a high/low logic output at 5VDC.

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/20191103_03November2019_12h45m.png" style="zoom:50%;" />
##Window Comparator
 A window comparator is a circuit (not a single component) that will respond to input voltages that deviate outside an acceptable “window” of values. In other words, the circuit responds anytime the variable input is either unacceptably low or unacceptably high.

<img src="file:///C:/Users/f126ck/Desktop/markEd/images/20191103_03November2019_12h46m.png" style="zoom:50%;" />

## Other applications
A comparator can be used as a zero point finder when its variable voltage input is attached to an AC signal.

**A continuous converter changes its output promptly in response to a change in input. This requires continuous current consumption. Because many applications only need to check the output from a comparator at intervals, power can be saved by using a clocked or latched comparator.**

## Oscillating Output

 The high input impedance of a comparator is vulnerable to stray electromagnetic fields. If the conductors leading to and from the comparator are relatively long, the output can couple capacitively with the input during voltage transitions, causing unwanted oscillations. SOLUTION add 1µF bypass capacitors to the power supply on either side of the comparator.

If a chip contains multiple comparators, and one of them is unused, one of its input pins should be tied to the positive side of the voltage supply while the other should be tied to 0V ground, to eliminate the possibility of an oscillating output.

# Op-Amp

An op-amp is an operational amplifier consisting of multiple transistors packaged in an integrated circuit chip. It senses the fluctuating voltage difference between two inputs, uses power from an external supply to amplify that difference, and uses negative feedback to ensure that the output is an accurate replica of the input. Its amplification can be adjusted by changing the values of two external resistors.

Many chips are available containing two or more op-amps. This is often expressed as the number of channels in the component.

The op-amps derived from 1970s designs often tolerate a wide range of power-supply voltages. Plus-or-minus 5VDC to plus-or-minus 15VDC is a common range. Modern op-amps are available that run from as little as 1VDC to as much as 1,000VDC.

Op-amps are available for frequencies ranging from 5KHz all the way up to 1GHz.



LM741: The most current it will draw from an input is around 0.5µA

VIO is the input offset voltage. In an ideal component, the output from an op-amp should be 0V when its inputs have a voltage difference of 0V. In practice, the output will be 0V when the inputs differ by the offset voltage. VIO is likely to be no greater than a couple of mV, and negative feedback can compensate for the offset.

Slew rate at unity gain is the rate of change of the output voltage caused by an instantaneous change on the input side, when the output of the op-amp is connected directly back to the inverting input (during operation in noninverting mode).

Can an op-amp that is designed for dual voltages be made to run from a single supply, such as 30VDC?

This is relatively easy to do. The op-amp simply needs a potential difference to power its internal transistors, and 30VDC on the V+ pin with 0VDC on the V− pin will work just as well as +15VDC and -15VDC. However, referring back to Figure 7-6, if the op-amp is used in inverting mode, an intermediate voltage must be supplied to the noninverting input. Likewise, in noninverting mode, an intermediate voltage is necessary for one of the inputs, and must be half-way

![](images/20191103_03November2019_16h57m.png)

## Offset Null Adjustment

 Some op-amps provide two pins for offset null adjustment, which is a setup process to ensure that identical voltage on the two inputs will produce a null output.

## Bad connection of unused sections/ channels

<img src="images/20191103_03November2019_17h01m.png" style="zoom:33%;" />

# Digital Potentiometer

This component is an integrated circuit chip that emulates the function of an analog potentiometer.

Possible applications include adjustment of the pulse width of an oscillator or multistable multivibrator (e.g., using the Control pin of a 555 timer chip); adjustment of the gain in an op-amp; specification of voltage delivered by a voltage regulator; and adjustment of a bandpass filter.

• Reliability. The digital component may be rated for as many as a million cycles (each storing the wiper position in an internal memory location). An analog component may be capable of just a few thousand adjustment cycles.
• Digital interface. • Elimination of long signal paths or cable runs. The digital potentiometer can be placed close to other chips, whereas an analog potentiometer often has to be some distance away to enable control by the end user. Reduction in the length of signal paths can reduce capacitive effects, while elimination of cable runs will reduce manufacturing costs.
• Reduction in size and weight compared with a manual potentiometer.



A digital potentiometer changes the point at which a connection is made along a ladder of many fixed resistors connected in series inside the chip. Each end of the ladder, and each intersection between two adjacent resistors, is known as a tap. The pin that can connect with any of the taps is referred to as the wiper, because it emulates the function of a wiper in an analog potentiometer.

No specific schematic symbol represents a digital potentiometer. Often the component is shown as an analog potentiometer symbol inside a box that has a part number,

Any type of digital potentiometer requires memory to store its current wiper position, and this memory may be volatile or nonvolatile. Nonvolatile memory may be indicated in a datasheet by the term NV.

Taper Digital potentiometers are available with linear taper or logarithmic taper.

SPI. This acronym is derived from serial peripheral interface, a term trademarked by Motorola but now used generically. The standard is adapted in various radically different ways among digital potentiometers

• I2C. More correctly printed as I2C and properly pronounced “I squared C,” this acronym is derived from the term inter-integrated circuit. Developed by Philips in the 1990s, it is a relatively slow-speed bus-communication protocol (up to 400kbps or 1Mbps in its basic form). It is built into some microcontrollers. The standard is more uniformly and rigorously defined than SPI.
• Up/down, also sometimes known as pushbutton or increment/decrement protocol.

The one feature that all versions of SPI have in common is that a series of high/low pulses is interpreted by the chip as a set of bits whose value defines a tap point in the resistor ladder. In computer terminology, every tap point has an address.

Typically, there will be a chip select pin, identified as CS; a serial data input pin, identified as SDA, SI, DIN, or a similar acronym; and a serial clock pin, identified as SCL, SCLK, or SCK, which must receive a stream of pulses to which the high/low data input pulses must be synchronized.

In addition, the SPI protocol allows bidirectional (duplex) serial communication. 

CS is usually, but not always, pulled low to activate the digital potentiometer for input. A series of low or high states is then applied to the datainput pin. Each time the clock input changes state (usually on the rising edge of the clock pulse) the state of the data input is copied to a shift register inside the chip. After all the bits have been clocked in, CS can change from low to high, causing the contents of the shift register to be copied into a decoder section of the chip. The first bit received becomes the most significant bit in the decoder. The value of the eight bits is decoded, and the chip connects the W pin directly to the corresponding tap along the ladder of 255 internal resistors.

Achieving Higher Resolution For sensitive applications where a resolution with more than 1,024 steps is required, multiple digital potentiometers with different step values can be combined.

<img src="images/20191103_03November2019_19h07m.png" style="zoom:33%;" />

In this circuit, the wipers of P2 and P3 must be moved in identical steps, so that the total resistance between the positive power supply and negative ground remains constant.

# Timer

A device that creates a single timed pulse, or a series of timed pulses with timed intervals between them, is properly known as a multivibrator, although the generic term timer has become much more common and is used here

A monostable timer emits a single timed pulse of fixed length in response to a triggering input that is usually of shorter duration. Many monostable timers are also capable of running in astable mode, in which the timer spontaneously emits an ongoing stream of timed pulses with timed gaps between them.

In monostable mode, the timer emits a pulse in response to a change from high to low voltage (or, less commonly, from low to high voltage) at a trigger pin.

The length of the pulse will be determined by external components, and is independent of the duration of the triggering event, although in some cases, an output pulse may be prolonged by retriggering the timer prematurely.

A monostable timer can control the duration of an event, such as the time for which a light remains on after it has been triggered by a motion sensor.

Astable Mode In astable mode, a timer will generally trigger itself as soon as power is connected, without any need for an external stimulus. However, the output can be suppressed by applying an appropriate voltage to a reset pin.

The duration of a single pulse in monostable mode, or the frequency of pulses in astable mode, is most commonly determined by an external RC network consisting of a resistor in series with a capacitor. 

A comparator inside the timer is often used to detect when the potential on the capacitor reaches a reference voltage that is established by a voltage divider inside the chip.

## NE555

<img src="images/20191103_03November2019_19h27m.png" style="zoom:33%;" />

The resistances inside the timer function as a voltage divider, providing a reference of 1/3 of V+ to the noninverting pin of Comparator A and 2/3 of V+ to the inverting pin of Comparator B

When power is initially supplied to the timer, if the Input pin is at a high state, Comparator A has a low output, and the flip-flop remains in its “up” position, allowing the Output pin to remain in a low state. The flip-flop also grounds the lower end of R1, which prevents any charge from accumulating on capacitor C1.

If the state of the Input pin is pulled down externally to a voltage less than 1/3 of V+, Comparator A now creates a high output that changes the flip-flop to its “down” position, sending a high signal out through the Output pin. At the same time, C1 is no longer grounded, and begins to charge at a rate determined by its own size and by the value of R1. When the charge on the capacitor exceeds 2/3 of V+, it activates Comparator B, which forces the flip-flop into its “up” position. The Output pin goes low, C1 discharges itself into the Discharge pin, and the timer’s cycle is at an end.

The low voltage on the Input pin of the timer must end before the end of the output cycle. If the voltage on the Input pin remains low, it will re-trigger the timer, prolonging the output pulse.

The Reset pin should normally be held high, either by being connected directly to positive supply voltage (if the reset function will not be needed) or by using a pullup resistor. If the Reset pin is pulled low, this will always interrupt an output pulse regardless of the timer’s current status.

555 Astable Operation In Figure 9-3, the 555 timer chip is shown with external components and connections to run it in astable mode. The pin names remain the same but have been omitted from this diagram because of limited space. The labeling of the two external resistors and capacitor as R1, R2, and C1 is universal in datasheets and manufacturers’ documentation.

When the timer is powered up initially, capacitor C1 has not yet accumulated any charge. Consequently, the state of the Threshold pin is low. But the Threshold pin is connected externally with the Input pin, for astable operation. Consequently, the Input pin is low, which forces the flip-flop into its “down” state, creating a high output. This happens almost instantaneously.

<img src="images/20191103_03November2019_19h37m.png" style="zoom:33%;" />

While the flip-flop is “down,” the Discharge pin is not grounded, and current flowing through R1 and R2 begins to charge the capacitor. When the charge exceeds 2/3 of positive supply voltage, Comparator B forces the flip-flop into its “up” position. This ends the high pulse on the Output pin, and starts to drain the charge from the capacitor through R2, into the Discharge pin. However, the voltage on the capacitor is still being shared by the Input pin, and when it diminishes to 1/3 of V+, the Input pin reactivates Comparator A, starting the cycle over again.

When power is first connected to the timer, C1 must initially charge from an assumed state of zero potential to 2/3 V+. **Because subsequent cycles will begin when the capacitor is at 1/3 V+, the first high output pulse from the timer will be slightly longer than subsequent output pulses**

Still, the longer initial pulse can be noticeable when the timer is running slowly.

Because the capacitor charges through R1 and R2 in series, but discharges only through R2, the length of each positive output pulse in astable mode is always greater than the gap between pulses. Two strategies have been used to overcome this limitation.

#5555 Timer 

The 5555 contains a digital counter that enables it to time very long periods. Its full part number is 74HC5555 or 74HCT5555, although these numbers may be preceded or followed by letter combinations identifying the manufacturer. **It is not pin-compatible with a 555 timer.**

4047B Timer 

This 14-pin CMOS chip was introduced in an effort to address some of the quirks of the 555 timer while also providing additional features.

Dual Monostable Timers Various timers that run only in monostable mode are available in dual format (i.e., two timers in one chip). This format became popular partly because two monostable timers can trigger each other to create an astable output, in which the pulse width, and the gap between pulses, can be set by a separate resistor-capacitor pair on each timer. This allows greater flexibility than is available when using a 555 timer.

When choosing values for R1 and R2, a minimum for each resistor is 5K, although 10K is preferred. Lower values will increase power consumption, and may also allow overload of the internal electronics when the chip sinks current from C1

A high-value capacitor may cause the timer to function less accurately and predictably, because large capacitors generally allow more leakage. This means that the capacitor will be losing charge at the same time that it is being charged through R1 + R2. If these resistors have high values, and the capacitor has a value of 100µF or more, the rate of charge may be so low that it is comparable with the rate of leakage. For this reason, a 555 timer is not a good choice for timing intervals much greater than a minute. If a largevalue capacitor is used, tantalum is preferable to electrolytic.

## Separate Control of High and Low Output Times

 In Figure 9-15, a bypass diode has been added around R2. The capacitor now charges primarily through R1, as the diode has a much lower effective resistance than R2. It discharges only through R2, as the diode blocks current in that direction. Consequently, the length of the high output pulse can be adjusted with the value of R1 only, while the length of the low output pulse can be adjusted with the value of R2 only. The duration of the high output can be lower than, or equal to, the duration of the low output, which is not possible with the basic configuration of components in Figure 9-14.

<img src="images/20191104_04November2019_22h11m.png" style="zoom:33%;" />

![](images/20191108_08November2019_10h01m.png)

# Flip Flop

Transistors enable logic gates; logic gates enable flip-flops; and flip-flops enable many mathematical, storage, and retrieval functions in digital computing.

A flip-flop is the smallest possible unit of memory. It can store a single bit of data, represented by either a high or low logic state.



Flip-flops are especially useful in counters, shift registers, and serial-to-parallel converters.

The asynchronous SR flip-flop is of primary use in debouncing switches. Examples are the single MAX6816, dual MAX6817, and octal MAX6818.

# Shift Register

A shift register most commonly is designed to store eight bits, although some store four.

When a pulse from an external clock is received by the shift register, all of the bits in storage are moved along one step, from each flip-flop to the next.

It is still useful for purposes of serial-parallel or parallel-serial conversion, and for small tasks such as scanning a matrixencoded keyboard or keypad.

A shift register generally consists of a chain of Dtype flip-flops. See the entry describing flipflops

The simplest shift register functions as a serial-in, serial-out device, abbreviated with the acronym SISO.

Parallel In, Serial Out 

A minority of shift registers are able to function as parallel-serial converters (parallel in, serial out, represented by the acronym PISO)

Buffering 

A shift register may also be used as a buffer between two circuits where the clock speeds are different. Digits are clocked in by the first circuit, then clocked out by the second. Some shift registers allow two clock inputs and can be used for this purpose.

# Counter

A counter can be used to count events, or can measure time in convenient intervals if it is connected with a component such as a quartz crystal that operates at a precise and reliable frequency. The counter receives input pulses (usually referred to as a clock input) and counts a predetermined number of them before restarting from the beginning.

A counter is built from a chain of flip-flops, with each one triggering the next. JK, T-type, or Dtype flip-flops may be used. For a thorough description of a flip-flop, see Chapter 11. In Figure 13-3, a D-type flip-flop is shown, triggered by each rising clock pulse.

![](images/20191108_08November2019_13h21m.png)



In a counter, to obtain a modulus that is not a power of two, logic gates inside the chip can intercept a particular value (such as 1010 binary, which is 10 decimal) and use this as a signal to restart the count at zero. External connections to the chip can achieve the same purpose.

All counter chips use binary code internally, and the number of bits (binary digits) in the counter’s modulus will be the same as the number of internal flip-flops. A 4-bit counter (the usual minimum) will have a modulus of 24 which is 16. A 21bit counter (the maximum typically available) will have a modulus of 221 which is 2,097,152. For higher moduli, counters can be chained together, each sending a carry signal to the next. This is known as a cascade.

A decade counter is a modulus-10 binary counter

To intercept binary 1010 (decimal 10), an internal NAND gate is used. Its output goes low when its two inputs, from Q1 and Q3, go high. The output from the NAND immediately activates the CLR function on all the flip-flops, so that as soon as the decade counter reaches 1010 (decimal 10), it resets itself to 0.

![](images/20191109_09November2019_13h17m.png)

The counter’s datasheet should include a state diagram showing how the counter will deal with this situation. It may reset itself to a valid value after a maximum of two steps, but this can still cause confusion, depending on the application

## Clock Sources

 The clock input may be provided by a timer chip or by an RC network, which has the advantage of being able to run at a relatively low speed for purposes where this is desirable. It may alternatively be provided by a quartz crystal oscillating at a much higher frequency such as 1MHz. Successive counters may be necessary to reduce this value, depending on the application.

![](images/20191109_09November2019_13h24m.png)

Descending Output 

Most components only create an ascending count. The output can be converted to a descending count by passing each binary state through an inverter, but this will only work properly if the modulus is equal to the number of states. In a BCD counter, its inverted outputs will count from decimal 15 to decimal 6, not from decimal 9 to decimal 0.

With suitable logic, this can enable a userspecified delay period

Programmable Counters 

A programmable counter can usually allow a modulus ranging from 2 to more than 10,000. The counter counts down by dividing an initial number repeatedly with a value that is preset with binary inputs. An example is the 4059B chip.

Lock-Out This is the condition which occurs if a counter with a shortened modulus is loaded with a binary state that is out of its range. Consult the datasheet and study its state diagram to determine the most likely outcome if this problem occurs.

## Asynchronous Artifacts 

Because the flip-flops in an asynchronous (ripple) counter do not change simultaneously, they create very brief false outputs while the ripple process is taking place. In a 4-bit counter, the binary number 0111 (decimal 7) should be followed by 1000 (decimal 8). However, the rightmost digit (i.e., the least significant bit) will change to a 0 initially, creating 0110 as a momentary binary output (decimal 6). The carry operation will then change the next digit to a 0, creating 0100 (decimal 4). The carry operation continues, changing the next digit to a 0, creating 0000. Finally the operation completes by creating 1000 as the correct output.

# Encoder

An encoder is a logic chip that receives an input consisting of an active logical state on one of at least four input pins, which have decimal values from 0 upward in increments of 1. The encoder converts the active pin number into a binary value represented by logic states on at least two output pins. This behavior is opposite to that of a decoder.

* 4-to-2 encoder

* 8-to-3 encoder

* 16-to-4 encoder 

In the early days of computing, encoders processed interrupts.

However, they are still useful in small devices—for example, if a large number of inputs must be handled by a microcontroller that has insufficient pins to receive data from each individually.

In an encoder, an active logic state is applied to one of four or more input pins, while the rest remain in an inactive logic state. The input pin number is converted to a binary code which is expressed as a pattern of logic states on two or more output pins.
• In a decoder, a binary number is applied as a pattern of logic states on two or more input pins. This value determines which one of four or more output pins will have an active logic state, while the rest remain in an inactive logic state.
• A multiplexer can connect a choice of multiple inputs to a single output, for data transfer. The logic state of an enable pin, or a binary number applied as a pattern of logic states to multiple control pins, chooses which input should be connected with the output pin. The alternative term data selector evokes the function of this device more clearly.

An analog multiplexer may allow its inputs and outputs to be swapped, in which case it becomes a demultiplexer. It can connect a single input to one of multiple outputs, for data transfer. The logic state of an enable pin, or a binary number applied as a pattern of logic states to multiple control pins, chooses which output should be used. The alternative term data distributor evokes the function of this device more clearly.

![](images/20191109_09November2019_15h10m.png)

![](images/20191109_09November2019_15h12m.png)

Cascaded Encoders

 Encoders are often provided with features to facilitate handling additional inputs via multiple chips. Typically, a second Enable pin is provided, as an output that connects with the Enable input of the preceding chip. This preserves the priority function, so that an input on the second chip prevents any additional input to the first chip from affecting the output. In a datasheet, the enable pins may be labeled EIN and EOUT, or EI and EO.
In addition, a GS pin will be included, meaning “Group Select.” It is logically active only when the encoder is enabled and at least one input is active. The GS pin of the most-significant encoder provides an additional binary digit.
The outputs from two encoders can be linked via OR gates, as shown in Figure 14-6, where the lower chip’s GS output provides the most significant bit of a four-bit binary number.

![](images/20191109_09November2019_15h15m.png)

# Decoder

A decoder receives a binary-coded number on two or more input pins. It decodes that number and expresses it by activating one of at least four output pins.

Decoders with 2, 3, or 4 input pins are common. To handle a binary input greater than 1111 (decimal 15), decoders can be chained together,

* 2-to-4 decoder

* 3-to-8 decoder

* 4-to-10 decoder

* 4-to-16 decoder

The input pins of a decoder can be driven by a counter that has a binary-coded output. A decoder can also be driven by a microcontroller, which may have an insufficient number of output pins to control a variety of devices. Two, three, or four of the outputs can be used to represent a binary number which is passed through the decoder to activate the devices one at a time, perhaps with transistors or Darlington arrays introduced to handle the load. 

A shift register can be used for a similar purpose, but often has only one pin for input

LED Driver A special case is a seven-segment decoder designed to drive a seven-segment LED display numeral. A binary-coded decimal number on four input pins is converted to a pattern of outputs appropriate for lighting the segments of the display that will form a number from decimal 0 through 9.

(The Latch Enable pin freezes the current state of the outputs (i.e., it latches them) when it is held low.)

Generally speaking, pins labeled A0, A1, A2… in a datasheet are often the binary inputs (although A, B, C… may be used), with A0 designating the least significant bit. Outputs are usually labeled Y, and are activated in sequence from Y0 when the binary input starts counting upward.

![](images/20191109_09November2019_15h32m.png)

![](images/20191109_09November2019_15h34m.png)

![](images/20191109_09November2019_15h35m.png)

# Multiplexer 

A multiplexer can select one of two or more input pins, and connect it internally with an output pin.

All multiplexers are digitally controlled devices, but may be described as either digital or analog depending how they process the input signal. A digital multiplexer creates an output that is adjusted to logic-high or logic-low within the limits of its logic family. An analog multiplexer does not impose any processing on the voltage, and passes along any fluctuations. Thus, it can be used with alternating current.

![](images/20191109_09November2019_15h39m.png)

Because an analog multiplexer merely switches a flow of current, it can be bidirectional; in other words, it can function as a demultiplexer, in which case the input is applied to the pole of the (imaginary) internal switch and outputs are taken from the terminals.

## Differential Multiplexer 

A differential multiplexer contains multiple switches that are differentiated from one another (i.e., they are electrically isolated, although they are controlled by the same set of select pins). A differential multiplexer is conceptually similar to a rotary switch with two or more decks controlled by a single shaft.

![](images/20191109_09November2019_15h42m.png)

Modern multiplexers are often found switching high-frequency data streams in audio, telecommunications, or video applications.

The multiple inputs to a multiplexer are referred to as channels. Almost always, the number of channels is 1, 2, 4, 8, or 16. A 1-channel component is only capable of “on” or “off” modes and functions similarly to a SPST switch.

The switch analogy is appropriate in that when an output from a multiplexer is not connected internally (i.e., its switch is “open”) it is effectively an open circuit. However, some multiplexers contain pullup resistors to give each output a defined state. This can be an important factor in determining whether the multiplexer is suitable for a particular application.

![](images/20191109_09November2019_15h45m.png)

below **multiplexer**

![](images/20191109_09November2019_15h46m.png)

below **demultiplexer**

![](images/20191109_09November2019_15h57m.png)

Most multiplexers are “break before make” devices, where one input is disconnected before the next input is connected. However, some exceptions exist, and datasheets should be checked for this.

The on-resistance is the resistance imposed by the analog multiplexer on the signal flowing through it. While modern, specialized analog multiplexers may have an on-resistance as low as 5Ω, these are relatively unusual. An on-resistance of 100Ω to 200Ω is more common.

Leakage current is the small amount of current (often measured in picoamperes) that the solidstate switch will pass when it is in its “off” state. This should be insignificant except when very high-impedance loads are used.

A multiplexer can also be used as a digital volume control by switching an audio signal among a variety of resistances, similar to a digital potentiometer. In this application, the possible presence of pullup resistors inside the multiplexer must be considered.

Multiplexers may be cascaded to increase the inputs-to-outputs ratio.

Modern multiplexers are found on computer boards where they choose among video output ports, or as PCI express channel switches.

**A multiplexer may be used as a parallel-to-serial converter**

In telecommunications, a multiplexer can sample voice signals from multiple separate inputs and combine them into a digital stream that can be transmitted at a faster bit rate over a single channel.

