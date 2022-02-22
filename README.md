# CMOS Logic Circuit Design

- **CMOS** is divided into two types:

**1]nMOS**

![nMOS](https://user-images.githubusercontent.com/70748543/155127352-316f6dbd-a4c0-4313-b064-a119aca1d002.JPG)

**2]pMOS**

![pMOS](https://user-images.githubusercontent.com/70748543/155127450-adb414ed-dd13-441b-bd63-81b6c32a7abd.JPG)

***
- **Working of nMOS and pMOS**

**1]nMOS** :

       CASE-1: If the gate voltage is “0”, nmos will be OFF, and Drain to Source will act as an open circuit.

       CASE-2: If the gate voltage is “1”, nmos will be ON, and Drain to Source will act as a short circuit.

**2]pMOS** :

       CASE-1: If the gate voltage is “0”, pmos will be ON, and Drain to Source will act as a short circuit.

       CASE-2: If the gate voltage is “1”, pmos will be OFF, and Drain to Source will act as an open circuit.
***
- **Structure of CMOS circuit:**

![Basic Diagram](https://user-images.githubusercontent.com/70748543/155127752-bae6495e-9a30-4571-a3a2-998c8e872e44.JPG)

-**Pull up network** is made using **pMOS** and **Pull down network** is made using **nMOS**.

-Pull up network will be connected to **Vdd** and Pull down network is connected to **GND**.

-**Output** will be taken between pull up and pull down network.

-**pMOS** transistor can easily pass logic **high**.

-**nMOS** transistor can easily pass logic **low**.

-We will always get an inverted output so we need to connect the inverter circuit at the output to get a non-inverted output.
***
- **Basic logic circuit rules**:

-For logic circuit design, we perform two operations:

**1] “ . ” operation or AND operation**: For “ . ” operation pMOS transistors will be connected in parallel and nMOS transistors will be connected in series.

**2] “ + ” operation or OR operation**: For “ + ” operation nMOS transistors will be connected in parallel and pMOS transistors will be connected in series.
***
- **Examples**:

**1]NAND Gate**:

![NAND GATE TRUTH TABLE](https://user-images.githubusercontent.com/70748543/155127824-f7fa6951-5960-4a3f-8433-cf2cfabf5a33.JPG)

![NAND GATE](https://user-images.githubusercontent.com/70748543/155127876-ea5e5ca8-59d6-448b-8eba-9ad3818e13c2.JPG)

***
**2]NOR GATE**:

![NOR GATE TRUTH TABLE](https://user-images.githubusercontent.com/70748543/155127931-b0d14b86-a7ff-4579-91e5-482c70d03d80.JPG)

![NOR GATE](https://user-images.githubusercontent.com/70748543/155127971-ea08eb69-6968-457d-97e2-111521992b70.JPG)

***
