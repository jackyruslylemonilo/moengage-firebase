Replace GoogleService-Info.plist with your firebase project GoogleService-Info.plist (ios/rnfb/GoogleService-Info.plist)

Replace MoEngage_APP_ID in info.plist with your moengage app id

curl -X POST --header "Authorization: key=FIREBASE_KEY" \
    --Header "Content-Type: application/json" \
    https://fcm.googleapis.com/fcm/send \
    -d "{\"to\":\"USER_KEY\",\"notification\":{\"title\":\"Hello\",\"body\":\"Yellow\"}}"