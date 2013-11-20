Hey Doc, this is me normally!
=========

Here's my password, look me up and in 30 - 60 seconds of video get a sense of what 'normal for me' is like.

Oh, and some of that annoying stuff like my NHS numbers, next of kin, allergies and a list of my other doctors.

#### Why?

When you meet a doctor or nurse, often you're acutely unwell, and you're just "not yourself".
Giving medical staff a quick glimpse of what you're like when you're well is more powerful than anything you can describe.
For older people, a video that shows doctors and nurses what they were like in mind, body _and spirit_ before this acute episode could be extra valuable.

A video of 'me on a good day' is also a great way to help HCPs make a relationship with us that respects who we are beyond being a patient.

### Minimum viable implementation feature list 
_(don't add nice-to-haves to this list!)_

1. 30-60 seconds of video (not about your health - it's a 'me on a good day' video)
2. Ability to create and maintain a secure account
3. Password-based access for an outsider to view your account
4. Basic text information (that you control)
  - NHS Number
  - Contact details
  - Next of kin
  - Allergies
  - Medications 
    - quick list (for excluding clashes/side effects)  
    - regime (times, doses, strengths)
  - List of other people involved in your care
    - with contact details
    - including specialists, school nurses, therapists etc
  - Other notes
    - free text section that we can use to inform next features
5. Doc can save/delete shortcuts to profiles (but can _only_ view online)
6. Users can store the profiles they own locally to view offline
7. QR codes are generated for individual users for Drs to get instant access to their profiles.
8. Usage by HCPs requires an nhs.net email account
9. When your profile is accessed by an HCP, you receive an email to let you know.

### Tech spec basics 
_(platforms, programming languages, infrastructure)_

- web (for uploading, editing)
- iPhone
- Android
- Dual develop in AS3 initially to get xPlatform prototype?

### User Stories
#### Doctor using an app (suggestion by @wai2k)

Dr Smith sees Mrs Brown who is not feeling well. He wants to know more information about Mrs Brown. He takes out his phone, launches this app and photographs a QR code that is on Mrs Brown wallpaper on her phone. To use this app, he pre-registers his phone and confirms his identity using his nhs.net email account. He now gains access to Mrs Brown information. Mrs Brown and her nominated next of kin immediately get notified via SMS/ email of the identity of the person that has viewed her record. If this is not authorised, the QR code is reset and a new one is generated.

### Active contributors
####Users

####Build team
  - Stray / [@betabetic](http://www.twitter.com/betabetic)

### Current top naming suggestions 
_useful as a sanity check for your minimum viable implementation_

### TODO list of next-steps
- technical
- user research
  - get reaction input from Kaz & Dominic
  - get reaction input from some Drs
  - distill to minimum viable implementation feature list
  - cross check MVI with users
- user testing
- visual design
- text
