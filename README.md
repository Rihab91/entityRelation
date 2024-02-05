# create the according Entity relationship model.

Relationships:
Gymnasium (1) --- (0..n) Member
Gymnasium (1) --- (0..n) Session
Member (0..n) --- (0..20) Session
Session (1) --- (0..2) Coach

Members can register at a gymnasium.
Members can attend sessions.
Sessions are held in a specific gymnasium.
Sessions can have a maximum of 20 members.
Sessions are led by coaches.
A coach can lead multiple sessions.
