# Ngrok
INSTALLTIONS
curl -sSL https://ngrok-agent.s3.amazonaws.com/ngrok.asc \
	| sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null \
	&& echo "deb https://ngrok-agent.s3.amazonaws.com buster main" \
	| sudo tee /etc/apt/sources.list.d/ngrok.list \
	&& sudo apt update \
	&& sudo apt install ngrok
 ADD THE TOKEN AUTOMATICALLY
 ngrok config add-authtoken 2siIOyDtsp9UEiG4KiC1OLO82RC_3Xm2a6jGYqFzGzXq1L238
 ////To navigate through the changes made in the terminal
 cd /usr/bin/
