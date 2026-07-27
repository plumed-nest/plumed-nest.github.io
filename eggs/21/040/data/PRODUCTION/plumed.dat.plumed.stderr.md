**Project ID:** [plumID:21.040]({{ '/' | absolute_url }}eggs/21/040/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @38 : cannot understand the following words from the input line : REF0=34.307,44.84,8.469, REF1=35.495,45.583,5.476, REF2=34.303,44.744,12.551, REF3=35.512,45.661,9.382, REF4=34.387,44.82,16.569, REF5=35.575,45.562,13.575, REF6=34.384,44.724,20.65, REF7=35.593,45.641,17.481, REF8=34.468,44.799,24.668, REF9=35.656,45.542,21.675, REF10=34.464,44.703,28.75, REF11=35.673,45.621,25.581, REF12=34.549,44.779,32.768, REF13=35.737,45.521,29.774, REF14=34.545,44.683,36.849, REF15=35.754,45.6,33.68, REF16=34.63,44.758,40.868, REF17=35.818,45.501,37.874, REF18=34.626,44.663,44.949, REF19=35.835,45.58,41.78, REF20=34.71,44.738,48.967, REF21=35.898,45.48,45.973, REF22=34.707,44.642,53.049, REF23=35.915,45.559,49.88, REF24=34.791,44.717,57.067, REF25=35.979,45.46,54.073, REF26=34.787,44.622,61.148, REF27=35.996,45.539,57.979, REF28=37.207,50.967,0.94
[runnervmvrwv9:08778] *** Process received signal ***
[runnervmvrwv9:08778] Signal: Aborted (6)
[runnervmvrwv9:08778] Signal code:  (-6)
[runnervmvrwv9:08778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fae1c845330]
[runnervmvrwv9:08778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fae1c89eb2c]
[runnervmvrwv9:08778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fae1c84527e]
[runnervmvrwv9:08778] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fae1c8288ff]
[runnervmvrwv9:08778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fae1cca5ff5]
[runnervmvrwv9:08778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fae1ccbb0da]
[runnervmvrwv9:08778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fae1cca5a55]
[runnervmvrwv9:08778] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fae1cca5a6f]
[runnervmvrwv9:08778] [ 8] plumed(+0x146dd)[0x560f77c356dd]
[runnervmvrwv9:08778] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fae1c82a1ca]
[runnervmvrwv9:08778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fae1c82a28b]
[runnervmvrwv9:08778] [11] plumed(+0x15365)[0x560f77c36365]
[runnervmvrwv9:08778] *** End of error message ***
</pre>
{% endraw %}
