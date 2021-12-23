# Skull-3D-reconstruction
This is a reconstruction of the 3d structure of a skull by using photos

<p align="">
  <img src="https://github.com/AlbertoMoca/Skull-3D-reconstruction/blob/main/readme_images/photo.png" width="400" />
</p>

For this we first need to take pictures from any structure around them in this case we used thresholds and median filters to clean the images and find the borders to then with these make the reconstruction

<p align="">
  <img src="https://github.com/AlbertoMoca/Skull-3D-reconstruction/blob/main/readme_images/cleaning.png"  width="400"/>
</p>

<p align="">
  <img src="https://github.com/AlbertoMoca/Skull-3D-reconstruction/blob/main/readme_images/perfil.png"  width="400"/>
</p>

<p align="">
  <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUUFBgVFRUYGRgaGBsZHBsbGR4cHRkbGRoZHiAeHRsbIy0kHCssIBoaJTclKS8wNTQ0GiM5PzkyPi0yNDABCwsLEA8QHhISHTIpIyk1MjIyMjIyMjIyMjIyMjIyMjIyNTIyMjIyMjIyMjIyMjIyMjIyMjsyMjIyMjsyMjI7Mv/AABEIALMBGgMBIgACEQEDEQH/xAAcAAEAAQUBAQAAAAAAAAAAAAAABwECAwUGCAT/xABDEAACAQIEAgcFBQYFAgcAAAABAhEAAwQSITEFQQYHIlFhcYETMpGhwSNCsdHwFFJicpLhFTNTgsIl8SRDY3N0g6L/xAAXAQEBAQEAAAAAAAAAAAAAAAAAAQID/8QAGxEBAQEBAAMBAAAAAAAAAAAAAAERIQIxQRL/2gAMAwEAAhEDEQA/AJmqlKUClKUClKUClUmrBdXQ5hroNRr5d9BkpWM3Brvp4H5aa+lWXsSiAs7BFAksxyqP9zQBQZ6Vz/Del+DxF8YezeFy4VLQvaUBYntjsnfkTXQUCqExVaj/AK471y3grb22ZSuIScrFTDJcH3SJ7RXQ6VLR3ubuHx0/vXyrfy+/cTUmJgenvd0/oa+Xrl+48Frlxj2Szl27JbSPejvA229K3nRPFpaLXMiM7NlVnykkKGzGXkAsTqNJ7+VW7CdT/e43h1AL37CgzBN1BMHlO+mtfLielmBtxnxdlZ1E3EM6xpBPx2qAull5Lji6qWwzKc4AALQ6bgbNLHUQYG/Ic2WGrGCA85CWkzJ840gmZ1FZmrj14jAgEbHUVdWHCqQig7hVnzgVmrSFWe0ExInunX4VfXmTj/E79niGMFq9eQjF3oRHdQZuXNeyw1kqQOc1KPS4uqZggxvBmPhQ3BE6x4An5ATUA9HOmnEDdRbmMuFCC5lUY5dRlGdPeJKwQSPjXYcW6wb9oK9kJcSSHFxSMoJgFbiEAgEiRkJ10mmiTy+2+vgfn3etY1vy5XKYAnNIiZIjeZ0PLlUV8P64C5K3MJoAZZLsho1gB0Gscs013HQ/pVa4laa5ZR0CMEIcKDOUHTKSIgj56U0dHSlKoUpSgUpSgUpSgVWqVWgpSlKBSlKCy4gYEHYiDXzphwAVEEaSG1kctd/jO1fXWNtNfj5fr600fPiMWlpGuXYRUWWY7Ko1Oo5CuG4t1tYO2WFm3cvldCwARJ10zN2uR+7XYdJrGfB4lP3rF0DSdSjRod9a8ui7kUZYRlIkGSWYyCYII7O0GOW5k1BK3D+sLEYy6y+0Fi0AultR7RmYElS75wACrDMqjQjY1wXS8l8Tna5euWyAQXdrjIshWAZ/GIkD3lFYOj90MGtiQYzs0yAEmSBy0KjmSY7q+fG271y4wM5VjUnTLKwSJ11I/QqfV+Ov6n2niSyBJsXGkEaglIBA0WIOkA9ryqfq8/8AVFhSnE0JIM27g0/l/tNegKsQrj+tDB+14dcUtlAe2xJEgAONxzGtdhXNdYaTwzFeFvN6KysfkDVECWrNlM6C47KArKVCpLZiCCHUk6ZDHgddKxC4lkZGZgrdqCJj1A5nl4ViW/bg9pYnQZhInz8t6zo5uGE7ZEbdo+G3l8qvldmM+My6wW8PbuuWGYxkhWEBzmAyrz1E1vrPQXFYi2HtYfJq3vtkDCBEC4+aJzctoMmuo6N4q1ZRXWwof3Q5WWYxqQzSRJB0BG1bfEdJrgJPtE0iUCyCT93PO8Ttt41ieecjpfHepJS4p0BFZKjwdJQyhgojvV5ZT4odRXT8A4obmZHdGdQGGXfKf3hyI+tWVLG8rzL1hYdv8UxJUEH2siDG6odPjXpqvPXWGw/xTErp71uRpzs2jpPjNVHK8Ld0YjIeakgxAJGjAbjNl35x4V9/FcVc9mVbUNAJA1gfLuFYHMqUiAdiNDuvMb7eVUw9sj37hcRAn7plddfAEetM6fGuVhBzKVRiWVVzASJHZLTMaDWfOp06llIwVyY/zoWO72ds7xrqxPOJjYCoit5VcPCkjMR2QcpjQgERuZ9Km/qwVv2IlgoLXnJCKqjZR93c6anedOVW5jPddnSlKjTmusNivDcSRIYJIIMENmWCDy1io16J9Z92yUtY0e2B09oq/bIQSn2g2ubDUdqDuxMCR+so/wDSsX/7f/Ja87cAu5cTbYELlOYTr2lU7aczqAfjzqD1DwzH2cQntLNzOvumCZUjdXVtVYcwwB76+zKeTd+4H0javP3HOkd2zdt4qzcKXimVimntSp09qh0YZSRrrosbSJB6IdZ1nFMljEL7K++UKR2kdjplB1KNOmVvDWTFNEg6+Ef2/OqZjzHdsfjvG1M/cD+Hf3+XzFCT4AeJ8vDz591UXA+BH68KvrCJkd3gI795M923dWagVjLgfqT8BVxE0AoLQT3c+dfLxDGLZtteuNlS2pZiByHcNSTyAGpJivtqJesvpCl+5cwSmVtWy7w0Zrx0Qae8qEyRrLFZHZqUdh0B482Ow9y84K/buFHIJlRkAPOFYA/xZq6qoy6jrk4O+oiBiMwAmFzW7fZ7WukR5g6nepNpBhdMysp5gr6EV5SwvDm1z9mACARqTIjQgjUGdf8Av6wbTX4+VebOMyuIxFsdrLeuiI29k9wb7wFWd/wq/R8V8Os5cocmGJEGBAiBpplGlMOWUAE5mzZpO0jbTbTX41uOCdG8XiwvsLLFNftH7FsluYcjtCAB2cxmpA4L1U21hsXda4f3LconkW99vMZacHH9W1yeK2FE6C6Y3yj2T6nu1MetT3XxcN4ZZw6ZLNpLa7kIoEnvJ3Y+J1r7aBWHEWFuIyOqujCGVgGVgdwQdCPCs1KD47XDbKRktW1jbKiiPKBpWXEq2R/ZwGytl7s0GJ9az0qYIOwhuC2g0IyjTz15edXXLxRcuQAd0V9HGeEHD4i5bt3GyoeyGhjBVWGojbMB5VrLvtueSD5/iTWfy1+lcHiVtvmOYdxVVaPRtvOuo6I8Zz4xcq5VaVc6szSDlLH+bLXE3rmTXc1sujGKJxmHVcwJupITcgMCZ71AEnwBpDU61qOJ9G8HiSWvYa07mBnKDPA27Y7WnnW3pW2XC4zqvwL/AOWb1rWYV8wkxyuBiNuRG/lXO4/qnugH2OJR5IIW5bKbfxqW7zyH1qXKUEAcS6A8StyRhg4/9K4rD0DkOfhUpdWWFe1w62txGtvmuko6lWX7RgJB11AB9a62lApSlByvWWyjheJzCQVRY8WuIo28SK8+Hh6h5zZQpAJOozTEAjvO3KvRXTvhd3FYC9ZsgG42RlBOXMbdxHKydASFIE6SRJG9efrlojPbuIVZSUZGBDKQdQR4fURTB83HSVdZAIyFRMmDPvDXuy/PStt1fWxd4lhpBuMbguEt9xkzMe/NspzHnHOtcMFKlGYuDASd1JI2PyjxrfdWNlbPEUuXGAS3bu3GY7KvsicxI2gGD5+lSznS16HAPM/AVcBFavgHFhi8OmIRSFuZioOjZQ7KCeWoAMcp51slYH+9JdFc2sc6vrEqRruTuf1yrLVFjzyIHmJ+opBnfTuj60cwNp8BH1qhfwPPlO3lQYb6NkYK5DZTDQsgxppEfGvLnCHZnuMWOdlJMt2iWKuCJ1OoJJ8RXqn2g5mPPTlPPwry1ItYu+SRFpryg9/aZQB3/OoJN6h2ITFKx7Ra0/PZhcEnxJU/KpbqI+pfETdxCAATbts3eWDMPQdo6eNS5VCubw/QrApffEGyr3XcuWuduCTPZVuysd8T410lKYApSlApSlApSlApSlBGnWKoGIUqxDNbGYAAxDNHxB2/hFclcvQup275+c19vHMecRiLjOrLLEDMIOUHs6H+HLWo/YA2udiPEzU0x87Wy5Ebb+lS71c4RUwVtsihibilgoDMBceJO5/tUe4XCquijT8fWpZ6MW1XCWQrBgUzSDIliWMHwJI9KSLrbUpSqhSlKBSlKBSlKBXLdL+h1nHrm9y+ohbgG4Ewrj766+Y5HUg9TSg818V4Xdwl02ryZHALDXR1B0ZCPeHjvyMERXzcXwVy1ZtucqLfDnX3iluGClTyLKI7z85R65ON2beHGHKK99yHSd7AE/aCIIJIKgTB7RMgEGMOlN/7DDJmk21VR39ldT3bgH1HiTLdMTl1dH/peGIED2ZgEzAztEmNYHOK6UJprrO/65VzfVuhHC8ID/pT6FmI+RrqKosCxzMdx1+e9ZKpVaClKo3lNUDA/r6UF1ebukuFVMfjVI1OJdwx2hzniPDP8tq9HMY5T+vlUGdPMA9ziz2V1a69sqAv3nt20k84lBJ5AExT6Nf0O6UW+GX2uvZe4LtvICGysqq5JIVuywYqBM6FCu4My7wPp5gMWAEvi25A7F37NteQzdlu7sk1F3W5wm1hbmGQKxQYRbSEaEPadjmY7NmDtI0M6zUf2jnYTl7KnRsqAhV1E6SSB5k6ak6xXrqledOhnFMWtwpYxj2bWaEV19qupJA9nJC9ndhGxg6V3adZdzDOLeOsBp2u4fNlcd6pcieUjNOu21NRKFK0PBelmDxcexvoWOyNKOY3hGgnzEit9VClKUClKUClKUELdL7V8Yi5cv23QM7BWI7LKDCAMOyewBpM1pVP3QSB4aV6AdARBAIO4OoNc/xHobg7s/ZezY/etnJHjl934ipi6jHBXL1x/wBmtJmd4UN3Kd2aBoADM/oy9wHha4XDpZUzlGrfvMTLGOUknTlVvBeBWcKpFpYJ95jqzRtLeHcNK2tJDSlKVUKUpQKUpQKUpQKUpQecOtS6y8VxAOoPsomGygW7Z0B93UNpzBOmta7iFn2htOV7BRCTqCC2sCDGqr8BpG9bHrZtH/Fb6r972TevskX4aVrreJzKBrCKiA95RACfSIqTon/oQhXh2FAj/ISBHeojWa3pY90+R18N4HzrUdDrpfAYZju1lGOkalQduVbuqLQ3gefyq+qVWgpWO55SeX/flVzkxoJNVFBZ2h4/I1zK8Az8WOMYdlMMiJP+ozXQx81QAf8A2V1VKCIevuyfZ4R9YD3FPdLKhHr2T86h29eDkEoqwqg5ZE5REmZ1O57zU+9c/D/a4FDMFL6t5gpcWB4yV+FQbc4WwUNnUzPgQRG49ag3HRi6FuMlti0MSsyuYFYE9xgfKtr0labebKwdIcT3g6yfvDKWrRdGMGwuuXGUqkqTtmzKBr6/Otp0kuXBZn2ZgHKZOgz/AIjly3FMXXK3Ef3gOy5aACYBEEgDlGZfiK6jg/TvGYOVt4k3EGoW5NwaA6asSo8FYd/fPKYi8DogKrp2SQdQBJJAE6yddpjxrI9v2TOl1CWCwAGAykhSpmDIg7CPe3oj1fwzEG5Ztu0Bnto5jaWUExPnX11rOjTTg8MZmcPaM9/2a1s6S7NClKVQpSlApSoG62sXfXiD21vXlQ2kdVFxwg0IMgGBJX3u8a8yJaJzvYhE1Z1X+ZgPxrV4npVgbc58XYEbj2ikj0BJrzBYKy3tFYtkIXUAhhpJzTpqdBBkCCKYTDOwd1y5UEuTEAMco8TqeU8qD0NiOszhaaftOY/w27h+eWPzqlnrBtXY9hhcVcDCVYoltG/la665vQHeoEsoMRctIDbtyEtE6wYiGaZ3IGwjUaVJGLxULuNgohzoF2gCJ7/TlU6uOi471h38MuZuHOoPus15GWdBDG3mymTEc65DH9cONEZMPYQEEjOHYkZiuhzKDqCJjcHurN/iJa21sqsMGDM7aNKkQfjzmosuNqQQJBiZJ2PI1fZmO9udZnEroJGIt2gEZuzbUEkbBfaSWJYxAJ0BPKtBiem3ELhGbGX40JyP7PWNfcifKtViL7XO0tsKqKqtkUwcumZz3knwHhWPD4p7ZcgDMyFDmUGA0TAYaGNJ37qYJf6l8Xcu3MQbl267hVJ9oSxUM2kMzEmcpkQI7zOku1DnUPYP/irjKYZ7Sq3LMq3ywPo6/wBQqY6SIUpSqIC6yMNm4tff91bQA7/s1JPpp8a1HDOGNiryYe0Ia40TuFB7TOf5Vk67xHOt91mgDiV3vK2z5fZoPoflXY9U/AfZ2mxbjt3Rlt94taGf97Cf5VQ86njyI7rhuCSxaSyghLaKigmTlUACTz2r6WEj+8fMVdSqrEtoAz2vVmPyJrNVKrQUpShNApVmbuHrsKBe8z+FByfWdaD8NvawVNt53ylbifQketQVceSzADfNB21I0UEnv5k869D9LsKb2CxNpBmdrLhVAklgsqI5SQIrznqCUdWS6ph0dSrCI1g6jfY0iV912+Ub2glzbYIDoJQyg8tx5TVcbxFbtl7YJDNAysDpBDSDz1UfE1hIbsiZUaiDMZgJ8thNWsiyrH7rA6aHyplXWixWEe2YcbgEHkQQCPkRWCukvp2YbVpIIj7uVYM/GtZjcCszbmNND5CY9ZoPTPQozw7B/wDxrPytrW8rn+gbzw3CaR/4e2P6VA+ldBUnoKUpVClKUCoL66cRctY5ShAF3CKjdkGQLtwncGDtqINTpUI9ftqL+Ffvt3F/pZT/AMqlEbWsMz22clQEKrJZQTmmAVJkjskZtcugOhEfCwI0Mgg7HkatrOhzwp94aKfD91vDuPLy2ordKBUKZs+peYyzPZy8zpvPOpHN+2bYcKgLAFSByIEa1H2H4ezFQVYdoAyInWDB5V31pLYj7NRlAG+gVRG2x8PKg1HEbr2kN2NJAGu5Jrlcdi2vObj5Q2VR2VCjsgKOyNBoB8K6/pWyXgoDlUUzlOhYkRMeE6eE1ocfwb2dx0LhipiVgr5AgkVItam1iHQMFYgMIYA6MByI599YRW6HB1yFy+oYLk5kEE5togRHqK+duHnk0elXES51GAfs+JPuk3rY+CjSPGSPWpZqOup7A+ywd0BlfNeDCJgTbtdkzzUz8KkWpApSlURF0m4P+3cc/ZwCEFtHvMOSAa6zoWBVBG0zyNSzathVCqAAAAABAAGgAHKvjw3DES7evD37xTMYEhUQKqg9wOZvNjX25Bz18/y2oBcd/wANfwqmY8h8TH5mrwI0qtBaAe/5VfVKrQWnwrHIHex+P4aCshE1Wgsknw89fkPzoF7yT+u4VfSgAVqON9HsPjFyYi0rx7rbOv8AK6wy+h151t6UEN9IerC/b7eEcXlH3HIW56HRH/8AxtsTXB4hGRmt3FZHX3ldSrL5g6ivUFarjXAcNi1y4i0rxsdmX+VxDL6GkuJY84ZDlLQSARr4mYE+QPworpDSCZAC8o13PpUh9Iuq68kvg3F1R/5b5Uuf7WEI3qF23NRvjA1lyl5Gtuv3XQgj0I28djV2Ueh+gL5uHYUn/TA/pJA+Qroq5Pqxu5uGYdpnS4J8BeuAfIV1lZkydUpSlUKUpQKiTr1wjOMIwIAU3lPf2xaI0/2NUt1HfXJanC2W7r0f1I/5CpRDGEwltc/tVLHI2XYQ+kT4b1kweFZ2CW1EnYDnX045lZwyiAVXT+IKA3xYE/7qtzZG7J5DXb3l1+EkelaxNZHLNbRPaRlcsveMwA96P4V56fh8dxsSohbjEkwQXE+O50r6Wfsx3EmRzmBE+EfM1mDhtDHgT+B/P9Bi60w4ezEm48nnBk+RY/Sa2mUCBlA21knQgd5il6Rp+pqyzLHlO4nnGsfLbntVR9GKykllAVWdsqzJUCCAfQgT4GseUMiKoBeWJgHNGkDuI0J011M8qwK86FgBvJMDQHnXzNjQp7JM8o+hoJx6qQP8OckGDduTHPsqDHftXeVxPVI2bhltoiXunz+0YfSPSuztnsjWdBr36b1lV9KUoFKUoFKUoFVqlVoMbtA0BPlH1IojSNiPAx9CavpQYmc/uE+q/U1lpSgxAvzVY/mJ/wCNXPMaAE+Jj5wavpQY1zcwB5MT9BVXzco9avpQWpPOPStXxvgVnGJkv27dxeWZCWWd8rhgVPiIrbUoNV0e4MmCw6Ye0WyIWjNqe07MR6FiB4Ab1taUoFKUoFKUoFcP1s3MmBDnYXVDfyurr8swI7iAeVdxWn6T8BTHYdsPcZlRmViVjN2GDaSCBtFSjzWMakasKqcZb7/kam7BdVnDLcZ7L3D3vdYg688mUfERW+wvQ/h9uMuDw/gTbVj37sCa1+qmPPNrE27jfeLZdMqFjKrvA11IAJ/imtrhOCYu5omDxJ03NllXT+JwB869F2bKqIRVUdwAA+VZabTEDWegPErg1w6p3F7ieG4QsfrpEd334PqnxrD7TFWLamP8tWuGPNgvyNTVWE9nUbcx9R+X13ioxw3UzY09ri7znmUVU8/ez1vsH1YcOtgZrdy4RGr3GkkcyEyg/Cu0BnUVdQfDwvh9vD2xZsoEtrJVRsMxJO+vvFj619dsaDQDwGwqh3Hjp58x9fjSzEaCNTv/ADGaDJSlKBSlKBSlKBVapVaClKUoFKUoFKUoFKUoFKUoFKUoFKUoFKUoFKUoFWlfTyq6lBjkjx+R+FXhgarVCJoK0rHlI2Podfnv+O9Vnv0/CgsPZ1G3MfUfl9d8gM6irhWE9nUbcx9R+X13C65tPdr+e/hNVQ6trOvw0Gn19aqII7wastE849OZAgz6iPSgy0pSgUpSgUpSgVWqVWgpSlKBSlKBSlKBSlKBSlKBSlKBSlKBSlKBSlKBSlKBSlKBSlKDGUHLQ+H6g+tXa+dXUoMK76c9wdPUD9fnbbIzkazAPeIk8+Ws6flpmZZ7q+X2bZvf0ywVAEyYhtZ7m89O6nsfZSqAVWgUpSgUpSgVWqVWgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSgUpSg//Z"  width="400"/>
</p>


### Result
<p align="">
  <img src="https://github.com/AlbertoMoca/Skull-3D-reconstruction/blob/main/readme_images/result.png"  width="400"/>
</p>

