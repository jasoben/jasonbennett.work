+++
date = "2015-05-10T07:28:27-04:00"
title = "The Papercraft DC Motor: Animated Explanation"


+++

# Animated Explanation of Components 

## Magnets

Magnetism is a natural force that emerges from the motion of electrons. All elements, whether Iron, Aluminum, or Oxygen, have electrons orbitting their atomic nuclei.

Normally the electrons in these atoms are all orbiting randomly. But if we expose the atoms to a strong magnetic field, the electron orbits will align and the magnetic direction of the substance will align into a coherent magnetic field.

<video src="https://jasoben.github.io/dc_motor/public/images/animations/magnetic-atoms.webm" controls loop/>
### Magnetic Poles 

All magnetic fields have polarity, which means they point in a particular direciton. When magnetic fields are in line with each other, the magnets will attract.

<video src="https://jasoben.github.io/dc_motor/public/images/animations/magnets-attract-with-field-lines.webm" controls loop/>

The more available electrons there are in an element, the stronger the attraction. Elements such as Iron have many available electrons, whereas elements such as Copper do not.

When the magnetic fields oppose each other the magnets repel each other.

<video src="https://jasoben.github.io/dc_motor/public/images/animations/magnets-repel-with-field-lines.webm" controls loop/>

Just as with attraction, elements with more available electrons will repel more strongly.

## Induced Magnetic Field

A single electron flowing through a length of wire will induce a magnetic field around it.

<video src="https://jasoben.github.io/dc_motor/public/images/animations/electron-bar.webm" controls loop/>

The induced magnetic field will always spin counter clockwise. This phenomenon is known as the Right Hand Rule. Take your right hand and stick out your thumb. The direction your fingers curl is the direction of the induced magnetic field when the electron moves in the direciton of your thumb.

<img width="300" src="http://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Right-hand_grip_rule.svg/2000px-Right-hand_grip_rule.svg.png"/>

## Batteries & Current

When you connect a loop of wire to a battery, current flows through it in the form of electrons.

The electrons induce a magnetic field around them while flowing through the while in accordance with the Right Hand Rule.

<video src="https://jasoben.github.io/dc_motor/public/images/animations/battery.webm" controls loop/>

## The Electromagnet

Combining an induced magnetic field in a spiral of wire with an element such as iron that readily aligns with the induced field allows us to build an electromagnet.

The electrons flow through the spiral, inducing magnetic fields around them and through the iron core. The atoms in the iron align their magnetic fields with the induced magnetic fields and a strong magnetic field emerges.

<video src="https://jasoben.github.io/dc_motor/public/images/animations/electromagnet.webm" controls loop/>

## A Spinning Electromagnet in a Strong Magnetic Field

The DC motor is, at its essence, just an electromagnet attached to a spinning rod, housed in a frame that has strong magnets on the outside.

The strong magnets have the same polarity, so they produce an even magnetic field through the motor.

If we run current through the electromagnet the induced magnetic field will repel against the existing strong magnetic field, spinning the rod until the electromagnet is aligned with the strong magnetic field, where it rests.

<video src="https://jasoben.github.io/dc_motor/public/images/animations/withoutcommutator.webm" controls loop/>

Of coures, a motor at rest can't do anything, which is why we need...

## The Commutator!

The commutator is the little bit of metal that makes the motor spin continuously.

It is two halves of a metal circle separated by a gap, attached to the spinning rod. As the rod spins current flows one way through the commutator into the electromagnet, forcing it to align with the magnets on the outside.

<video src="https://jasoben.github.io/dc_motor/public/images/animations/withcommutator.webm" controls loop/>

THEN the momentum of the spin causes the rod to rotate just a hair fraction more, at which point the other half of the commutator makes contact with the opposite side of the battery through the contact points (or brushes). The current now flows the other way, inducing an reverse magnetic field.

It's important to remember that the rod has spun the electromagnet 180 degrees, so the electromagnet's reversed magnetid field is now pointing the same direction as it did when the electromaget was at rest.

This constant reset of the electromagnet into a state of repulsion drives the motor for as long as current is supplied.