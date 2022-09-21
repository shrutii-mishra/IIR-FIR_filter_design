# IIR-FIR_filter_design

## ABSTRACT

We are comparing the four types of filters ( lowpass, highpass, bandpass, bandstop) and with the help of iir(infinite impulse response) and fir(finite impulse response). So here the question is why we need to compare them and what’s the use of comparing them by using types of filters,  so the answer is now a days we see different types of headsets are releasing and one of the model in noise cancellation headsets,  here the noise cancellation headset works on the application of iir and fir so here we are going to differentiate them and going to know how the process takes place. and we will do by using matlab.
Here we have also worked on a process of BASS enhancement.

## EXPECTED OUTCOME

Here we get to know how the frequency varies between the filters and its applications , like with the example of noise cancellation headsets and we get to know what is iir and fir and how it works in different filters
Firstly we should know about IIR and FIR

### INFINITE IMPULSE RESPONSE(IIR)

A FIR filter has equal time delay at all frequencies and it is fast in processing and low ordered and it is unstable sometimes and not constant in delay

### FINITE IMPULSE RESPOSE(FIR)

A IIR filter has time delay varies with frequencies and it is slow in processing and high ordered and it is always stable and constant at delay

## Low Pass FIR Filter
### Matlab Code

![image](https://user-images.githubusercontent.com/91796225/191561780-ce7bfe4b-1a5e-4672-9c8e-af4e42fdedc9.png)

### MAGNITUDE RESPONSE

![image](https://user-images.githubusercontent.com/91796225/191561909-7b21ab59-610d-4069-8080-9b34468ff036.png)

## Low Pass IIR filter

### Matlab Code

![image](https://user-images.githubusercontent.com/91796225/191562108-2e4c49e4-8766-4fd3-9ee0-3764f7ef7429.png)

### MAGNITUDE RESPONSE

![image](https://user-images.githubusercontent.com/91796225/191562272-67f6be31-d482-49a0-9972-ed320dd819b1.png)

FOR THE ORDER N=9


Enter the sampling frequency of the sine signal (Hz): 100
Enter the amplitude of the sine signal: 1
Enter the input frequency of the sine signal (Hz): 1
Enter the phase of the sine signal (rad):0
Enter the pass band frequency fp =2000
Enter the stop band frequency fs  =3000
Enter the pass band attenuation rp = 0.9
Enter the stop band attenuation rs = 40
Enter the sampling frequency f	=10000

![image](https://user-images.githubusercontent.com/91796225/191562546-dbcf1dc9-5efa-41bf-b570-c28841da14d4.png)
![image](https://user-images.githubusercontent.com/91796225/191562607-9804f200-c2fd-456a-a0f9-1d8ad247d493.png)

## High Pass FIR Filter
### Matlab Code

![image](https://user-images.githubusercontent.com/91796225/191562824-cd7d6cc1-f0c0-4154-bffc-a7ea0029641f.png)

### MAGNITUDE RESPONSE

![image](https://user-images.githubusercontent.com/91796225/191562896-79d09970-f5ea-4f42-b791-285fdfba6bb5.png)

## High Pass IIR filter

### Matlab Code

![image](https://user-images.githubusercontent.com/91796225/191562960-6c574124-d126-4d55-9ab9-6f13f4492219.png)

### MAGNITUDE RESPONSE

![image](https://user-images.githubusercontent.com/91796225/191563022-cd5b0a48-c59c-4851-b3e1-e0516b13bf32.png)

## Band Pass FIR Filter
### Matlab Code

![image](https://user-images.githubusercontent.com/91796225/191563275-34960a8f-0a36-405d-857d-b4f7bbe1fcbb.png)

### MAGNITUDE RESPONSE

![image](https://user-images.githubusercontent.com/91796225/191563335-fd20da3a-f6c7-4cd1-b481-70ed61e48f3e.png)

## Band Pass IIR filter

### Matlab Code

![image](https://user-images.githubusercontent.com/91796225/191563443-0290f0c2-f262-44d8-be1c-6123450cc661.png)

### MAGNITUDE RESPONSE

![image](https://user-images.githubusercontent.com/91796225/191563631-f0017637-c049-4d6f-9a6c-ec57c034ee24.png)

## Band Stop FIR Filter
### Matlab Code
![image](https://user-images.githubusercontent.com/91796225/191563919-bf313f6c-a4a3-4edf-93e4-1f85b3813f38.png)

### MAGNITUDE RESPONSE
![image](https://user-images.githubusercontent.com/91796225/191563996-e8184341-7529-45a5-ae9b-0b2a6e66b824.png)

## Band Stop IIR filter
### Matlab Code

![image](https://user-images.githubusercontent.com/91796225/191564072-12781096-0732-407d-a2c4-673afa44b151.png)

### MAGNITUDE RESPONSE

![image](https://user-images.githubusercontent.com/91796225/191564128-d5dd99fd-323e-4c98-b591-6bd8f8c27fb4.png)

![image](https://user-images.githubusercontent.com/91796225/191564299-23fa40e1-e069-4eda-9b98-1c553b9386a8.png)
