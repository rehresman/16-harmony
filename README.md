# 16-harmony

is a lightweight 16-voice harmony generator

low rates -> it's a random sequencer

mid rates -> it's a chord generator

audio rates up to 20kHz -> it's a unique noise source

all quantize-able to unknown pentatonic scales

![64 harmony in action](https://github.com/rehresman/16-harmony/blob/main/cover.png)

this is a lightweight version of 32-harmony: https://github.com/rehresman/32-harmony  
buffest version: max polyphony, raspberry pi 4 norns only:  https://github.com/rehresman/64-harmony  

# installation  

1. clone/download this repo to ```dust/code```
2. restart norns
3. select -> 16-harmony

## parameters

**default**  
e1 - pitch  
e2 - decay  
e3 - range  

k1 (hold) - **shift**  
k2 - random scale  
k3 - II chord  

**shit**  
e1 - quantize  
e2 - rate  
e3 - lpf cutoff  

k2 - init scale  
k3 - V chord  

**default**

         ■            ●           
    shift (hold)    pitch 

                                                ●                  ● 
                                              decay              range

                                                ■                  ■
                                           rand scale         II chord (hold)


**shift**

         ■           ●           
    shift (hold)  quantize 

                                                ●                  ● 
                                               rate            lpf cutoff

                                                ■                  ■
                                            init scale       V chord (hold)



**parameters page**
attack