# EmotionProject
deep learning to identify emotion in faces

Using tensorflow (and keras), attempt to identify the emotion in a face - working off the Karolinska faces.

Caveats: only caucasian people, young adults. 

Challenge: images have front pictures as well as semiprofile and full profile on either side.

The Karolinska Directed Emotional Faces

Lundqvist, D., Flykt, A., &  Öhman, A. (1998). The Karolinska Directed Emotional Faces - KDEF, CD ROM from Department of Clinical Neuroscience, Psychology section, Karolinska Institutet, ISBN 91-630-7164-9.

Summary

The Karolinska Directed Emotional Faces (KDEF) is a set of totally 4900 pictures of human facial expressions. The set of pictures contains 70 individuals displaying 7 different emotional expressions. Each expression is viewed from 5 different angles.

Subjects

Population: 70 amateur actors, 35 females and 35 males.
Selection criteria’s: Age between 20 and 30 years of age. No beards, mustaches, earrings or eyeglasses, and preferably no visible make-up during photo-session.

Method

All subjects received written instructions in advance. These instructions entailed a description of the seven different expressions that they were to pose during the photo session. The subject was asked to rehearse the different expressions for 1 hour before coming to the photo session. It was emphasized that the subject should try to evoke the emotion that was to be expressed, and - while maintaining a way of expressing the emotion that felt natural to them - try to make the expression strong and clear.
	All subjects wore special gray T-shirts. They were seated at a distance of approximately three meters from the camera. The absolute distance was adapted for each subject by adjusting the camera position until the subject’s eyes and mouth were at specific, pre-defined vertical and horizontal positions on the camera’s grid screen. 
	The lights were set to cast a soft indirect light evenly distributed at both sides of the face. 
After a session of rehearsal, the subjects were shot in one expression at the time until all seven expressions had been shot (series one). The subjects were the shot once again in all expressions and angles (series two).

Equipment

Camera: Pentax LX.
Lens:  Pentax original 135 mm.
Extra: Grid screen.
Film: Kodak 320 T.
Lights: 3 * 500 W lamps.

Digitizing

Hardware: Macintosh 8500/120, Polaroid Sprintscan 35.
Software: Adobe Photoshop 4.
Settings: Positives (36 * 24 mm) were scanned in RGB color, in 625 dpi resolution.
Extra: Each picture was adjusted to a digital grid. Once again, vertical and horizontal position of eyes and mouth were adjusted to specific positions on the grid, and then cropped to a size of 562 pixels width and 762 pixels height.

Details

Copyright:  Psychology section, Department of Clinical Neuroscience, 
Karolinska Institute, Stockholm, Sweden.
Participants: 70 (35 males and 35 females).
Age: m 25 years, ranging from 20 to 30 years.
Expressions: 7 (neutral, happy, angry, afraid, disgusted, sad, surprised).
Angles: 5 (full left profile, half left profile, straight, half right profile, full right profile).
Sessions: 2.
Number of pictures: 4900.
Size: 562 * 762 pixels.
Resolution: 72*72 dpi.
Colors: 16.7 million (32 bit).
Size inflated: 1.6 Mb.
Size compressed: approximately 122 kb (ranging from 85 to 158 kb).
File format: JPEG.
Compression quality: 94 %.
Codes:
	Example: AF01ANFL.JPG
		Letter 1: Session 
					A = series one
					B = series two
		Letter 2: Gender 
					F = female
					M = male
		Letter 3 & 4: Identity number
					01 - 35
		Letter 5 & 6: Expression
					AF = afraid
					AN = angry
					DI = disgusted
					HA = happy
					NE = neutral
					SA = sad
					SU = surprised
		Letter 7 & 8: Angle
					FL = full left profile
					HL = half left profile
					S = straight
					HR = half right profile
					FR = full right profile
		Extension: Picture format 
					JPG = jpeg (Joint Photographic Experts Group)
# EmotionProject2
