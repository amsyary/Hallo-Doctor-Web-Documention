---
sidebar_position: 1

---

# Welcome

**First of all, thank you very much for purchasing this source code**.

This is a complete end-to-end solution for booking a consultation meeting with a doctor using Video Call and Payment from the user to the doctor, it include Admin Dashboard

## What It Is And How It Works

In the current situation it is sometimes difficult to meet a doctor face-to-face, and most people, many are also afraid to consult a doctor, because they might think the cost is quite expensive,
Now with the development of technology, we can solve that problem by using Video Call technology, client and doctors can conduct consultations from their respective homes
then a Helo Doctor application is made which will solve all the problems above, in this application the client will be facilitated in choosing the specialist he wants based on ratings and reviews as well as the price of the consultation
and the client is also made easy to pay, on the doctor's side, the doctor will be facilitated in setting the schedule using the timeslot the doctor can set the duration of the consultation and the price, and when the timeslot is purchased by the client the doctor can start a consultation session
according to the schedule, and after the consultation is complete and the client is satisfied with the consultation he can give a review to the doctor, and the client payment will be forwarded to the doctor
and we as this service provider, can take a cut from every transaction that occurs, that is a little explanation of this application, I'm sure after trying to run the application later you will fully understand this application

## Technology / Stack used in this app

- ReactJS with Typescript
- Redux Tool Kit State Management
- Firebase Backend
- VideoCall using Agora.io
- Stripe payment gateway

## App Feature

### Client

- Video Calling Doctor

- Login (with Google Login, or username & password) / Register / Forgot Password

- Top Rated Doctor

show all top rated doctor

- Search Doctor

you can search doctor by their name

- Doctor Category / Specialist

show all doctor category

- Doctor Detail

you can see doctor detail, like hospital, price, review, rating, biography . etc

- Doctor Timeslot

you can see all doctor timeslot that you can book, there is time, and price

- Purchase Timeslot with Stripe payment Gateway

you can purchase doctor timeslot using stripe payment gateway

- Order Detail

you can see your order detail

- Video Call

start consultation using video call

- Review & Rating

after consultation session you ban give review to doctor

- Problem

if something wrong, you can complain and payment to the doctor will be witheld, until problem resolve

- Edit Profile

you ca edit your email, and password

### Doctor

- Login / Register / Forgot Password

- Doctor Detail

doctor can add their detail such as Specialist, Hospital

- Calendar Timeslot

doctor can add Timeslot, with price, duration, and date

- Consultation List

doctor can see if there is consultation being purchase

- Video Call Consultation

doctor can start consultation session and client will be notified

- Balance, Money

doctor can see their balance add if consultation alredy ended

- Withdraw Money

doctor can withdraw their money using payment method that their chose(currently only support PayPal)

### Web Admin

- Dashboard Data (User Number, Doctor Number, ext)

- List Data of User

- List Data of Doctor

- List, Add, Edit, Doctor Category

- List Transaction

- List Witdhraw Request

and more
