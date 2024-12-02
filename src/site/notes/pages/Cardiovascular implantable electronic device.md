---
{"dg-publish":true,"permalink":"/pages/Cardiovascular implantable electronic device/"}
---


202411122108

Status: 

Tags: [[Cardiology\|Cardiology]], [[Equipment\|Equipment]], [[Knowledge/Medicine/ECG\|ECG]]

# Cardiovascular implantable electronic device
# Common problems
5 common CIED-related issues encountered in the perioperative period: 
1. [[pages/Cardiovascular implantable electronic device#Rapid pacing\|#Rapid pacing]]
2. “inappropriate” slow pacing, 
3. electromagnetic interference ([[pages/Cardiovascular implantable electronic device#EMI\|#EMI]]), 
4. overt CIED [[pages/Cardiovascular implantable electronic device#Device malfunction\|#Device malfunction]], 
5. [[pages/Cardiovascular implantable electronic device#Unexpected response to magnet application\|#Unexpected response to magnet application]]

The greatest concern over a ==paced ventricular tachycardia== would be a failure to recognize the tachycardia as a paced rhythm, leading to potentially harmful drug administration, external shocks, or case cancellation
## Rapid pacing
“Rapid pacing” is defined as ventricular pacing at a rate faster than the CIED's programmed base rate or “lower rate limit.”

Because ventricular pacing commonly creates a ==wide QRS==, the rhythm can be ==misinterpreted== as ventricular tachycardia

rapid pacing can lead to coronary ischemia, with resultant patient injury
### Tracking
As → Vp

The most common form of rapid pacing occurs when the ventricle is paced after each ==rapid intrinsic atrial rate P wave==. 
This phenomenon is referred to as “tracking,” and most commonly occurs with ==DDD== pacing in a patient with inadequate atrioventricular conduction

If the rapid ventricular pacing is due to tracking and the tachycardia represents a risk to the patient, the appropriate response is to ↓ intrinsic atrial rate ==pharmacologically== rather than to cardiovert
### Rate response tachycardia
Normal CIED function can create confusion when rapid ventricular pacing occurs via the rate-response feature. Also known as “rate modulation” or “rate adaptation,” this feature is used frequently in patients with ==chronotropic incompetence== (ie, inability to achieve a heart rate of 100 beats/min at maximal exertion)

Cardiovascular implantable electronic devices can detect physical activity in several ways:
- ==accelerometers== to assess body movement,
- ==minute ventilation== sensors to estimate chest expansion and respiratory rate, 
- changes in ==ventricular impedance==
These sensors, especially accelerometers, can ==misinterpret== extraneous signals such as stimulated muscle activity, hyperventilation, or external CIED motion due to manipulation of nearby structures

if device programming for surgery will be performed → rate-response feature should be ==inactivated==

If the rate-response feature remains active, the practitioner should consider this feature as the cause of an ==unexplained paced tachycardia==.
### Pacemaker mediated tachycardia
Pacemaker-mediated tachycardia (PMT, or pacemaker-induced tachycardia) is a ==reentrant arrhythmia== that typically is triggered by a ==retrograde P wave==

A ventricular depolarization that does not originate via the normal conduction system may find the conduction system not refractory, permitting conduction in a ==retrograde== fashion back to the atria. The ==retrograde P wave== is then sensed by the atrial lead of the CIED, setting up the next paced beat to the ventricle (“[[pages/Cardiovascular implantable electronic device#Tracking\|#Tracking]]”).

The total time for the full cycle is usually short enough to produce heart rates above ==100 bpm==.
This cycle can continue indefinitely

if the device is a ==pacemaker==, ==magnet== placement will break the cycle by converting the pacemaker to ==asynchronous== pacing, thereby eliminating the rhythm because there is ==no sensing== (thus no [[pages/Cardiovascular implantable electronic device#Tracking\|#Tracking]]) with asynchronous pacing

If the device is an ==ICD== and the patient is hemodynamically unstable, ==adenosine== or ==cardioversion== are potential treatments

despite termination, ==reinitiation== of the PMT can occur

Programming changes can prevent PMT, including ==lengthening== the post-ventricular atrial refractory period ([[pages/Cardiovascular implantable electronic device#PVARP\|#PVARP]]) or changing the pacing mode to ==DDI==, which will eliminate [[pages/Cardiovascular implantable electronic device#Tracking\|#Tracking]]
### Device features to prevent unwanted rapid pacing
Features worth understanding are
- [[pages/Cardiovascular implantable electronic device#PVARP\|#PVARP]],
- [[pages/Cardiovascular implantable electronic device#Upper pacing rate limits\|#Upper pacing rate limits]]
- [[pages/Cardiovascular implantable electronic device#Mode switching\|#Mode switching]]
#### PVARP
PVARP begins after either a paced or sensed ventricular depolarization. 
duration is programmable, but ==200-to-250 msec== is typical

During the PVARP, the CIED will still look for atrial depolarizations and count them toward the determination of the atrial rate, but will not use those atrial senses to then pace the ventricle (ie, atrial-sensed events during the PVARP will ==not be tracked==)

If ==retrograde== conduction becomes ==prolonged==, as could occur with the effects of ==anesthesia==, and a retrograde P wave occurs after the ==PVARP has ended==, PMT could be initiated
#### Upper pacing rate limits
Maximum pacing rates can be programmed for both the ==tracking== and the ==rate-response== features

Chosen values typically account for the ==exertional needs== of the patient and their ==ability to tolerate== faster rates

If the atrial rate exceeds the upper tracking rate, the device will attempt to pace the ventricle after each P wave, but will ==lengthen the P-R interval== to keep the ventricular rate no faster than the upper tracking rate.
Eventually, however, a P wave will occur during [[pages/Cardiovascular implantable electronic device#PVARP\|#PVARP]] and be ==ignored==. The cycle then reinitiates and produces a phenomenon known as "==pacemaker Wenckebach=="

If the atrial rate exceeds the upper tracking rate, the Wenckebach will become a 2:1 block.
#### Mode switching
One serious problem with tracking could occur if the patient develops atrial fibrillation or flutter
Although the upper tracking rate limits how fast the ventricle can be paced, letting the patient remain at such a high rate for a prolonged period could be harmful.
Thus, a device feature called “mode switching” exists to prevent rapid ventricular pacing

When the atrial rate exceeds a programmed value (commonly 170 beats/min), the pacing mode converts from an ==atrial synchronous== pacing mode (eg, DDD) to a ==nontracking== mode such as VVI, DDI, or VDI

Devices can require up to 8 fast atrial events before initiating the mode switch, but once it occurs, ==backup ventricular pacing== will be at the programmed mode switch rate that may be different from the base rate

Mode switching relies on the ==detection of a fast atrial rate==, but if the ==amplitude== of the atrial electrical activity is too low to be sensed or if an atrial signal occurs systematically during the short time after a ventricular depolarization when the atrial lead is not active, the pacemaker may not recognize enough atrial events to cause a mode switch and continue to pace the ventricle after those atrial senses

Should such undesired tachycardia occur in the operating room, treatment is difficult.
If the device is a ==pacemaker== and the patient has a heart block, then ==magnet== placement would convert the rhythm to ==asynchronous== pacing at a rate that is more reasonable.
Otherwise, the only solution is ==cardioversion== or interventions to the CIED that only can be accomplished via ==programming==.
## Pacing slower than the base rate
Pacing can occur at rates lower than the “base pacing rate” for reasons other than inhibition of pacing from electromagnetic interference
Although unlikely to harm the patient, it may be confusing and even be ==misinterpreted as a device malfunction==
### Sleep mode
Due to a desire to ==limit== the amount of pacing, Medtronic (Medtronic, Plc) and Biotronik (Biotronik Worldwide) CIEDs can be programmed to reduce the base pacing rate during ==sleep hours==. Devices from Abbott (Abbott Laboratories) can be programmed to pace at a lower rate at any time of day when patient ==inactivity== is sensed by the device.

If surgery occurs during these “sleep” or inactive periods, then a pacing rate below the expected base rate will be seen

Boston Scientific (Boston Scientific Corp) does not have a sleep mode.
### Hysteresis
This feature, if programmed on, will permit the patient's rhythm (==intrinsic heart rate==) to decrease to a value (eg, 50) that is ==lower== than the official base rate (eg, 60) before initiating pacing.

Once the intrinsic rate goes below the ==hysteresis rate== (eg, 50), pacing will then commence at the ==programmed base rate== (eg, 60)

The device will then check periodically to see if there is an intrinsic rhythm below the base rate but greater than the hysteresis rate
## EMI
Electromagnetic interference refers to the potential ==disruption== of CIED function by an ==external electromagnetic field==. The most common source of EMI intraoperatively is the electrosurgery unit, also known as " ==electrocautery=="

EMI can create ==sensing artefacts== in either the atrial or the ventricular lead or both

### Inhibition of pacing
The most common effect of monopolar electrocautery EMI is to produce ==oversensing==—pacemaker detection of depolarizations that did not occur

For any CIED programmed to ==demand pacing==, this will cause inhibition of atrial and/or ventricular pacing

Pacing inhibition due to ==oversensing== can cause profound bradycardia in patients with ==inadequate intrinsic rhythm==

If the CIED is a ==pacemaker==, ==magnet== placement usually will convert the device to ==asynchronous== pacing, restoring an adequate rhythm

If the device is an ==ICD==, the only option to prevent pacing inhibition is to ==program== the device to ==asynchronous== pacing because magnets do not convert ICDs to asynchronous pacing
Otherwise, the only option is to ==limit== electrocautery duration and frequency
### Inappropriate shock from ICD
With an ICD, ==oversensing== the EMI signals can be interpreted as a tachyarrhythmia and cause delivery of ==antitachycardia== overdrive pacing or inappropriate ==shocks==

The criteria for antitachycardia therapy is programmable. The basic strategy involves ==detecting fast ventricular rates==, with some fraction of a defined number of ==consecutive beats== required to be faster than a ==defined rate==. Once criteria are met, therapy commences, except there will be a ==delay== for a shock because the device must ==charge== the capacitors used to provide the shock

If criteria are met initially but go away before shock delivery, the shock is ==aborted==; but for a brief period thereafter, ==lesser criteria== are required to define a treatable rhythm.
This feature explains why ==short bursts of electrocautery== are not necessarily safe if ==administered too close== together

VT but no therapy:
When this occurs, examination of the programmed settings typically reveals that the ventricular tachycardia ==rate was below the minimal threshold== necessary to trigger antitachyarrhythmia therapy.
### Pacing due to EMI
The rate of the artefact detections determines which CIED feature might be impacted. The common thread is that all these disruptions result in some degree of ==ventricular pacing==.

most such unnecessary ventricular pacing is ==not at a dangerously rapid rate==, so their occurrence is an oddity that merely leaves the observer puzzled

As with [[pages/Cardiovascular implantable electronic device#Tracking\|#Tracking]], it is important to recognize the tachycardia as a ==paced rhythm== and not ==ventricular tachycardia== with inappropriate therapy administration

all the features described in this section ==do not exist== when ==asynchronous== pacing is employed, whether by programming the CIED or via magnet placement over a pacemaker.
#### [[pages/Cardiovascular implantable electronic device#Tracking\|#Tracking]]
Because the EMI can be detected by the leads and interpreted as a sensed event (depolarization), it could lead to [[pages/Cardiovascular implantable electronic device#Tracking\|#Tracking]] if the atrial lead sees “depolarizations” produced by EMI. For ventricular pacing to occur, the ventricular lead must fail to detect the EMI that would otherwise inhibit pacing

Sometimes, CIEDs are programmed to allow the ==atrioventricular (AV) interval== to ==lengthen== to facilitate intrinsic AV conduction.
This feature helps ==limit== the amount of ventricular pacing. If AV conduction fails altogether, then ventricular pacing commences.
Electromagnetic interference can fool this feature by creating electrical events in the ==atrial lead== interpreted as atrial depolarizations. Because no QRS would be expected after these artefacts, the device detects “==failed conduction==” and commences ventricular pacing
The device will check periodically to see if native conduction has returned.
This scenario cannot be prevented but will not harm the patient.
#### [[pages/Cardiovascular implantable electronic device#Mode switching\|#Mode switching]]
EMI detected in ==only the atrial== lead can result in [[pages/Cardiovascular implantable electronic device#Mode switching\|#Mode switching]] and subsequent ventricular pacing. 
Prevention of this scenario is not possible, but it is not likely to harm the patient unless ==misinterpreted== as ventricular ectopy.
#### Rate-drop response
The ==rate-drop response== is an advanced feature of pacemakers intended to provide backup pacing to ameliorate the symptoms associated with vasovagal episodes or neurocardiogenic syncope.
Although rarely programmed on, it can create confusion in the operating room.
If a patient's ==intrinsic rate decreases rapidly== or falls below a certain value, pacing commences at a rate ==considerably above the base rate== to support cardiac output

In the context of EMI, ==oversensing== can be ==misinterpreted== as a fast rate. When EMI ceases, the device then senses only the ==true== native R waves at an ==abruptly slower rate==, thereby meeting the criteria for a ==rapid decrease== in heart rate. 
This will trigger the rate-drop response, with AV pacing higher than the base rate

The rate-drop response can and probably should be ==disabled== for surgery.
#### Noise reversion
If EMI creates ==very high rates== of detections, then a feature known as “noise reversion” may initiate. Very high sensing rates cannot result from true myocardial electrical activity, so the device considers what it is seeing as “noise”

Because the device has no idea what the actual cardiac rhythm is, as a safeguard against bradycardia or asystole, the device will pace the heart. If the heart has its own rhythm, the pacing represents a ==competing rhythm==. In this situation, competing rhythms are presumably better than no rhythm

Noise reversion is available in all CIEDs except Medtronic ICDs and some older Abbott models. Often, noise reversion is a ==fixed== feature; but in some CIEDs, noise reversion pacing can be disabled

The pacing rate during noise reversion is often the base pacing rate, but it may be the sensor-indicated rate or even a fixed rate of 50 beats/min, depending on the manufacturer and model

If there is no concern that the patient would become pacing-dependent during surgery, if programming is performed, it should be safe to turn noise reversion off for surgery if possible.
## Device malfunction
True device malfunction at the time of surgery is almost always the result of preexisting issues with the device or the lead
### Inadequate battery reserve
When a strong EMI signal is encountered, such as from magnetic resonance imaging, radiation therapy, external defibrillation, or monopolar cautery applied too close to the device, battery ==voltage may decrease transiently==

If the battery voltage decreases below the minimal voltage for device function, the device will stop working

When the battery voltage recovers, the device does not restore to its original programmed settings, but rather to very ==basic default settings==. This event is called a " ==power-on-reset==," and is a fail-safe feature to minimize further battery depletion yet provide backup safety pacing.
These events are rare and are most likely to occur when the battery is near its end of life, and the battery voltage is barely above the minimum level. Most devices reset to ==demand== pacing (VVI or DDI), plus ==antitachyarrhythmia== therapy with ICDs.

In the operating room, after a ==power-on reset==, a device programmed for surgery to asynchronous pacing with tachyarrhythmia detection suspended would now be restored to demand pacing and active antitachycardia therapy, putting the patient at risk for [[pages/Cardiovascular implantable electronic device#Inhibition of pacing\|#Inhibition of pacing]] and undesired shocks.
in patients needing ==high heart rates==, the factory ==default base pacing rate== may not provide adequate cardiac output
### Lead malfunction
==Broken wires== and ==poor electrical contact== of the lead tip to normal tissue (eg, scarring) are the typical causes of malfunction.
These problems can result in
- undersensing,
- oversensing
- failure to capture.
With malfunction, patients may or may not present with symptoms, and the malfunction may be detected only by interrogation. 

When ==undersensing== (failure to sense) occurs, pacing spikes appear late in the conducted QRS or even after the completion of the QRS

==oversensing== can cause pacing inhibition due to sensed events that are not actual depolarizations, potentially leaving the patient severely ==bradycardic==. However, if the patient has a ==functional native rhythm==, minimal rhythm disturbance may be observed with oversensing
### Unexpected response to magnet application
A much more likely cause of magnet failure to prevent tachyarrhythmia therapy involves whether the ICD senses the presence of the magnet.

The ==location== of magnet placement can affect a device's ability to sense the magnet
Even with proper placement of a magnet, it could shift position during the surgery

If the ICD is implanted deep in the tissue, such as in patients with ==morbid obesity==, the magnet's field may be too weak to be detected

Some ICD has feedback e.g. beep sound

One advantage of using a magnet with a ==pacemaker== is that one can always test the magnet response before surgery
The magnet response in pacemakers primarily exists as a test of the ==battery== because the ==asynchronous pacing rate== decreases when the battery is near its end of life
If magnet placement is successful and asynchronous pacing is observed at a rate consistent with a healthy battery, then one can proceed with surgery with reasonable assurance of the expected magnet response
# General peri-op Mx
## Pre-op evaluation

|                   | No Interrogation                                                                                                                                                                                                                                                                                   | Recent Interrogation                                                                                                                                                                                                                                                                               |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Battery status    | Check magnet rate on pacemaker (see Supplemental Table 1).                                                                                                                                                                                                                                         | Provides battery status for pacemaker, ICD or Micra. Also provides device status.                                                                                                                                                                                                                  |
| Pacing Dependency | Lack of pacing on rhythm strip confirms non-dependency.  Presence of pacing may not prove dependency.                                                                                                                                                                                              | If pacing present, confirmation of an adequate underlying rhythm requires formal interrogation.                                                                                                                                                                                                    |
| EMI Risk          | Bipolar only – no risk.  <br>Monopolar: Low risk of pacing inhibition if surgical site below umbilicus. Risk of ICD shock is higher, despite surgical site.                                                                                                                                        | N/A                                                                                                                                                                                                                                                                                                |
| Magnet Use        | Magnet use is feasible if:<br><br>1.      Device is not buried deep in patient<br><br>2.     Magnet placement (centered or eccentric) identified.<br><br>3.     Device not in surgical field.<br><br>4.     Magnet can be easily accessed (e.g., patient not prone) and kept in a stable position. | Magnet use not feasible:<br><br>Pacemaker:  If patient is pacing dependent and EMI is likely to inhibit pacing, arrange for programing to asynchronous pacing.  <br>ICD†:  Arrange for programing to disable anti-tachycardia therapy and, if pacing dependent, programing to asynchronous pacing. |
## Intra-op Mx

|                                                               | **Setup**                                                                                             | **Action**                                                                                                                                                                    | **Additional Notes**                                                                                                                             |
| ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Monitoring                                                    | 1.    Display pacing spikes on EKG.<br><br>2.    Display pulse oximeter waveform if no arterial line. | Observe pulse waveform during cautery use to confirm presence of an adequate rhythm.                                                                                          |                                                                                                                                                  |
| Magnet                                                        | Confirm magnet response.                                                                              | Pacemaker:  apply magnet if an inadequate heart rate is observed.<br><br>ICD:  Place magnet over device.  Remove magnet if ventricular tachycardia/fibrillation is observed.† | If an inadequate heart rate is present during cautery and the device is an ICD, only device programming or pharmacologic intervention will help. |
| Unexpected paced ventricular tachycardia during cautery       | Most common cause is tracking (see text)                                                              | During cautery, can occur for many reasons (see text) but unlikely to be harmful.  Observe and document.                                                                      | Cause and prevention of further events requires interrogation and programming.                                                                   |
| Unexpected paced ventricular tachycardia without cautery use. |                                                                                                       | Treat sinus tachycardia if necessary.  Other causes include PMT or failure to mode switch during atrial fibrillation/flutter.                                                 | Pacemaker:  magnet application will halt PMT and may slow the ventricular rate during failure to mode switch.                                    |
## Post-op Mx

| **Criteria**                      | **Action**                                                     | **Device Interrogation**                                                                                                                                                                                                  |
| --------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Device programmed for surgery     | Continuously monitor patient until device can be interrogated. | Restore settings to baseline values and check device function.                                                                                                                                                            |
| Device not programmed for surgery | Remove magnet                                                  | Interrogation not necessary unless concern over device malfunction, extreme intraoperative cardiovascular instability or severe electrolyte imbalance. After elective surgery, device should be checked within two weeks. |
# Peri-op - St Jude
![](https://i.imgur.com/Jg7MoBr.png)

## Pre-op

| Recent interrogation                    | Pacemaker within ==12 months==                                                          |
| --------------------------------------- | --------------------------------------------------------------------------------------- |
|                                         | ICD/CRT within ==6 months==                                                             |
| Battery life                            | >3 months                                                                               |
| Leads                                   | >3 months since implantation                                                            |
| Capture threshold (chronic)             | <3.0 V                                                                                  |
| Safety margin                           | Autocapture - 1 V (atrial lead), 0.375 V (ventricular lead)                             |
|                                         | Fixed output - 2:1 ratio (pulse amplitude:capture threshold)                            |
| Lead impedance (ideal)                  | 300-1,200 ohms                                                                          |
| High voltage lead impedance (ICDs only) | 25-125 ohms                                                                             |
| Sensitivity (chronic)                   | P wave >1.5 mV                                                                          |
|                                         | R wave >4 mV                                                                            |
| Magnet response                         | Confirm the device response to magnet application                                       |
| Rate adaptation                         | Consider disabling for perioperative period                                             |
| Pacemaker dependency                    | Determine dependency via history, ECG, or interrogation                                 |
| EMI risk                                | Determine by the type, location, and nature of the procedure                            |
| Tachyarrhythmia history (ICDs only)     | Determine the number and type of events recorded                                        |
| Tachyarrhythmia treatment algorithm     | Determine the programmed parameters for the diagnosis and treatment of tachyarrhythmias |

## Intra-op
### ICD
Lack confirmation of proper magnet application (ie, tone emission)

An alternative means of malignant arrhythmias treatment (ie, external defibrillator) is required if “tachy therapies” are disabled

### Pacemaker
The magnet induced asynchronous pacing rate is 100 bpm and decreases to 86.1 at ERI (elective replacement interval)

## Post-op
Perioperative programming mandates postoperative interrogation
HRS & ASA recommendations favor interrogation in the postoperative period

# Peri-op - Boston Scientific
## Pre-op

| Capture threshold (chronic)           | <3 V                                                   |
| ------------------------------------- | ------------------------------------------------------ |
| Sensitivity (chronic)                 | P wave >2 mV                                           |
|                                       | R wave >5 mV                                           |
| High-voltage lead impedance (chronic) | >20 ohms and <200 ohms                                 |
| Magnet response                       | Confirm the device response to magnet application      |
| S-ICD                                 | Lacks bradycardia and antitachycardia pacing therapies |
## Intra-op

| ICDs       | Tone emitted in response to magnet application                                                                      |
| ---------- | ------------------------------------------------------------------------------------------------------------------- |
| S-ICDs     | Tone emitted in response to magnet application                                                                      |
| Pacemakers | The magnet-induced asynchronous pacing rate is 100 bpm with the rate decreasing to 85 bpm at ERI and <85 bpm at EOL |
|            | Magnet application results in fixed asynchronous pacing rate with a 100 millisecond (ms) AV delay                   |
|            | For CRT-P devices magnet application results in a left ventricle offset of 0 ms                                     |

# Post-op

The 2011 HRS/ASA Expert Consensus Statement provided specific guidance on postoperative interrogation of CIEDs with the management recommendations being stratified into the following 3 groups: 
- device evaluation before discharge from a monitored setting,
- postoperative device evaluation within 1 month,
- routine follow-up

Postoperative ==interrogation and programming== ==before discharge== or transfer from a monitored setting were deemed necessary if the CIED was ==reprogrammed== before the procedure (eg, tachyarrhythmia therapies were disabled)

==immediate== postoperative ==interrogation== is indicated when
- a surgery is
	- hemodynamically challenging,
	- remarkable for significant intraoperative events
		- (eg, cardiac arrest, temporary pacing, cardioversion),
	- emergency in nature
- electromagnetic interference exposure occurred above the umbilicus
- logistical challenges impedes the patient from being evaluated within 1 month

specific procedures were determined to be indications for ==interrogation before discharge== or transfer from a monitored setting; including 
- cardiothoracic surgery, 
- external cardioversion,
- radiofrequency ablation, 
- therapeutic radiation


> [!NOTE] ASA practice advisory 2011
> CIED ==postoperative== management should include an ==interrogation== in the PACU or ICU. 
> 
> However, it was acknowledged that in low-risk situations (eg, no possibility of intraoperative electromagnetic interference, no blood products administered, no perioperative programming occurred, no perioperative complications, and appropriate preoperative CIED evaluation occurred), a postoperative CIED evaluation may not be required


Anesthesia practitioners commonly operate under the following assumptions regarding magnet application to CIEDs: 
(1) magnet application to an implantable cardioverter defibrillator (ICD) will suspend tachyarrhythmia therapies temporarily (eg, anti-tachycardia pacing and defibrillation) but leave the bradycardia pacing settings unchanged (eg, DDD)
(2) magnet application to a pacemaker will result in sustained asynchronous pacing (eg, DOO) at a specific rate determined by the manufacturer and battery life of the device


> [!NOTE] HRS
> It is recommended by the HRS that a ==pacemaker== be interrogated within ==12 months== and ==ICD/CRT== (cardiac resynchronization therapy) devices within ==6 months== of elective surgery
> 
> Battery longevity >3mo

ASA/HRS recommends that leads be mature (ie, >3 months old) prior to an elective procedure

# Pacemaker dependency
Useful info to determine pacemaker dependence:
- indication for placement,
- preoperative 12-lead ECG,
- underlying rhythm
- paced rhythm on telemetry,
- percentage paced

there is ==no strict definition== of ==pacemaker dependency== based solely on percentage paced

it is often useful to re-confirm pacemaker dependence on the day of surgery

# Magnet
The practitioner must decide
- if a magnet can be placed easily
	- w/o causing patient injury
	- w/o interference with the surgical field
- if the magnet response can be tested,
- if the patient is pacing-dependent

St. Jude (Abbott) devices have a ==programmable== response to magnet application

Medtronic devices responses to magnet application
Pacemakers:
Asynchronous pacing at 85 bpm  <br>• First 3 beats at 100 bpm (exceptions EnRhythm and SureScan models)  <br>• 1 or more ventricular pulses may be emitted at a reduced pulse or voltage during the first 7 beats as part of a threshold margin test  <br>At ERI asynchronous pacing (VOO) at 65 bpm|

Defibrillators
Tachyarrhythmia therapies are suspended.  
Pacemaker settings (ie, bradycardia therapy) are left unaltered.  
Some devices will emit a tone for 15 to 30 seconds.

Aside from determining the risk of periprocedure electromagnetic interference, perioperative management largely depends upon
- mode,
- rate,
- rate adaptation,
- patient's dependency on the device for pacing,
- device response to magnet application

# Pacing threshold
The capture threshold, or threshold, is the least amount of electrical stimulus required to consistently depolarize the myocardium and result in contraction
typical pulse widths 0.4 to 0.6ms

commonly accepted chronic threshold measurements (at a pulse width of 0.5 ms) are <3.0 V

when a fixed output is programmed an acceptable safety margin needs to be maintained in order to guarantee capture. An accepted safety margin for a fixed output to threshold is 2:1

# Lead impedance
ideal impedance is actually in the range of ==300 to 1,200 ohms== (when measured at a pulse width of 0.5 ms)

==Low impedance== would result in wasted current or signify a lead insulation breach

==elevated impedance== would make pacing impossible due to an inability to capture the myocardium or signal the presence of a lead fracture or poor connection

# Capture threshold
- initial implant: <0.5V at 0.5ms
- chronic: <3.0V at 0.5ms
→ reflect device's ability to effectively ==pace== the myocardium
Programmed amplitude / pulse width should provide an adequate safety margin (e.g. pulse amplitude : capture threshold >2:1)

# Sensitivity
A device’s sensitivity is its ability to detect the patient’s intrinsic rhythm. This directly affects the appropriate function of the pacemaker and pacemaker inhibition due to electromagnetic interference

Overall, the ==greater== the amplitude, the more likely the patient’s own complex is to be sensed

Measured atrial (P) & ventricular (R) waves
- R wave: >4-5 mV
- P wave:
	- acute >2.0 mV
	- chronic >1.5 mV
→ reflect device's ability to ==sense== intrinsic activity

chronic leads = leads implanted for >= 30 days

# Rate adaptation
Continuation of rate adaptive therapy in the perioperative period may result in inappropriate heart rate changes. Therefore, the authors and anesthesiologists who follow the ASA and HRS recommendations prefer that rate adaptation be disabled

When rate adaptive pacing is enabled, one or more sensors detect a change in the patient’s activity level and increase the pacing rate accordingly

Strong consideration should be given to disabling rate adaptive pacing during the perioperative period, especially in devices in which ventilation is the monitored parameter (e.g. minute ventilation via thoracic impedance)

American Society of Anesthesiologists (ASA) concluded that the majority of consultants agree that rate adaptive therapy should be disabled perioperatively

If rate adaptive pacing is electively continued perioperatively, the paced rate may ==inappropriately increase== in response to factors including
- mechanical hyperventilation, 
- external respiratory rate monitoring,
- electrocautery, 
- succinylcholine-induced muscle fasciculations,
- postoperative shivering.

Intraoperative rate changes, which result from elective continuation of rate modulation, usually are ==benign==. 

 ↑ HR may be
 - hemodynamically significant
 - unfavorable for certain comorbidities
	 - (eg, coronary disease)
 - misinterpreted as patient discomfort.
## Close loop stimulation (CLS)
CLS is a form of rate adaptation that is related to the contractile state of the myocardium, predominantly involves the ventricular lead, and is unique to Biotronik devices

Given that this form of rate adaptation involves catecholamine stimulation and is based on intracardiac impedances at the lead tip, it is reported to provide appropriate responses to not only exercise but also emotional stress

CLS is theorized to be affected by myocardial ischemia and cardioactive medications

# ICD
ICD also contains one or more high voltage (HV) coils. The presence of these high voltage coils provides for tachyarrhythmia therapies in the form of low energy cardioversion or high-energy defibrillation.

# High voltage lead impedance
For St. Jude ICDs, 25 to 125 ohms is considered normal. However, an acute rise (eg, an increase from 30 ohms to 100 ohms over a 12-month period) may be indicative of a dysfunctional HV coil and should be investigated.

# Antitachycardia pacing
ATP involves termination of a tachyarrhythmia circuit by rapid or ==overdrive pacing==

Most modern ICDs will attempt to terminate a [[pages/tachyarrhythmia\|tachyarrhythmia]] by ATP for ==lower rate== [[pages/Ventricular tachycardia\|ventricular tachycardia]] (VT) or while charging for a shock because it is ==less painful== for the awake patient and utilizes ==less energy==, which optimizes device life

==alternative means== for the treatment of a malignant arrhythmia (eg, external pads and a defibrillator) should be readily available whenever tachyarrhythmia therapies are disabled
# Tachyarrhythmia history = arrhythmia burden
= how many events pt has had since last interrogation

This information may influence whether or not the practitioner relies upon the ICD for therapies perioperatively (ie, removes the magnet intraoperatively if a tachyarrhythmia is diagnosed) or requires additional monitoring.

# S-ICD (subcutaneous ICD)
consists of a single subcutaneous electrode and a pulse generator that are implanted for the prevention of ==sudden cardiac death== in select patients

S-ICD provides sensing, detection, and defibrillation therapy (synchronous, biphasic shock of 80 Joules) of malignant ventricular tachyarrhythmias in patients who have ==no need== for ==antitachycardia== or ==bradycardia pacing==

despite the lack of permanent pacing capabilities, the S-ICD can be programmed to provide ==transient bradycardia pacing== at 50 bpm for a maximum duration of ==30 seconds==, in the event that ==postshock bradycardia== occurs

Although there is a lack of societal recommendations regarding perioperative management of the S-ICD, the ==wider sensing region== and ==increased susceptibility== to EMI of the subcutaneous device strongly favors deactivation of shock therapy during the perioperative period

A standard doughnut-shaped magnet can be used to temporarily deactivate the device

magnet application to the S-ICD is ==different== from that used for transvenous ICDs. The manufacturer recommends magnet placement over the ==header== or over the ==lower edge== of the pulse generator, which typically is located in the 6th intercostal space along the left midaxillary line to suspend therapy

Optimal S-ICD suspension with a magnet occurs if the device emits a ==beeping== tone for 60 seconds after magnet application

even proper magnet application may not elicit the standard tone emission in patients with a “deep implant” or those previously exposed to a strong magnetic field

If magnet application does suspend therapies successfully, then magnet removal will restore arrhythmia detection and shock therapy.

Given that even proper magnet application may be ==ineffective== (eg, patients with a “deep implant”) or ==inconclusive== (ie, lack tone emission), the authors prefer programming for perioperative management


# CRT
### CRT-D
CRT-D devices pose specific dilemmas for perioperative management because the devices provide ==close to 100% biventricular pacing==, and the addition of a high-voltage coil indicates that magnet application will not result in asynchronous pacing

Although CRT patients often have an “adequate” underlying rhythm, the goal is ventricular synchronization via biventricular pacing, and inhibition due to electromagnetic interference (EMI) may result in a reduction in cardiac output

EMI-induced hypotension in the CRT patient population can result from the loss of biventricular pacing rather than asystole, which is a possible EMI effect in the pacemaker-dependent patient. Therefore, an ==asynchronous== mode may be indicated during the perioperative period

The addition of a ==high-voltage coil==, which implies the device is a ==defibrillator==, indicates that magnet application will not affect the pacemaker settings and interrogation/programming with a programmer would be required to institute an asynchronous mode.

placing a device in an asynchronous mode either via magnet application or programming is not necessarily benign because asynchronous pacing potentially can be pro-arrhythmic
e.g. [[R-on-T phenomenon\|R-on-T phenomenon]]

### CRT-P
Even though pacemakers and CRT devices without defibrillator capabilities (ie, cardiac resynchronization therapy-pacemaker = CRT-P) can respond to magnet application with asynchronous pacing, the settings are ==unlikely to be identical== to the patient-specific programmed values

for CRT-P devices, magnet application results in the ==LV offset== being set to ==0ms==

(LV offset = the time from the LV pacing pulse to RV pacing pulse)

Typically the ==LV offset== is a negative number (eg, –20 to –80 ms) and conveys that the ==LV pacing pulse== is delivered ==before== the right ventricle pacing pulse. Therefore, magnet-induced changes to the LV offset may affect synchronization and cardiac output

# MR Conditional
Specifics regarding acceptable MRI conditions such as
(1) the static magnetic field, which is measured in tesla (T);
(2) the radiofrequency field, which is measured by the specific absorption rate (SAR) in watts(W)/kilogram(kg);
(3) the pulsed gradient field, which is measured in T/meter(m)/second(s)


In general, MR conditional devices have been approved for scanning at 1.5 T, SAR ≤2 W/kg, and ≤ 200 T/m/s

| MR safe           | Device that is not a hazard in ==any== MR environment                                                        |
| ----------------- | ------------------------------------------------------------------------------------------------------------ |
| MR conditional    | Device that does not pose a known hazard in a ==specified== MRI environment with specified conditions of use |
| MR unsafe         | Device known to pose hazards in all MR environments                                                          |
| MR nonconditional | All CIEDs other than those granted MR conditional labeling                                                   |


> [!NOTE] Heart Rhythm Society expert consensus statement
> MRI scan on a patient with a recently implanted MR conditional device (eg, within ==6 weeks==) may be reasonable based on the clinical need
> 
> patients with abandoned, fractured, and epicardial leads be treated as having MR ==nonconditional== devices and evaluated for MRI as such



___
# References
[[Reference notes/Readwise/Articles/Fundamental Electrophysiology Principles Related to Perioperative Management of Cardiovascular Implantable Electronic Devices\|Fundamental Electrophysiology Principles Related to Perioperative Management of Cardiovascular Implantable Electronic Devices - JCVA]]

[[Reference notes/Readwise/Articles/Perioperative Interrogation of Medtronic Cardiovascular Implantable Electronic Devices A Guide for Anesthesiologists\|Perioperative Interrogation of Medtronic Cardiovascular Implantable Electronic Devices A Guide for Anesthesiologists - JCVA]]

[[Reference notes/Readwise/Articles/Perioperative Interrogation of St. Jude Cardiovascular Implantable Electronic Devices A Guide for Anesthesiologists\|Perioperative Interrogation of St. Jude Cardiovascular Implantable Electronic Devices A Guide for Anesthesiologists - JCVA]]

[[Reference notes/Readwise/Articles/Perioperative Interrogation of Boston Scientific Cardiovascular Implantable Electronic Devices A Guide for Anesthesiologists\|Perioperative Interrogation of Boston Scientific Cardiovascular Implantable Electronic Devices A Guide for Anesthesiologists - JCVA]]

[[Reference notes/Readwise/Articles/Perioperative Interrogation of Biotronik Cardiovascular Implantable Electronic Devices A Guide for Anesthesiologists\|Perioperative Interrogation of Biotronik Cardiovascular Implantable Electronic Devices A Guide for Anesthesiologists - JCVA]]
