**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmpptgkbjq6m:05885] *** Process received signal ***
[pkrvmpptgkbjq6m:05885] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05885] Signal code:  (-6)
[pkrvmpptgkbjq6m:05885] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b30645330]
[pkrvmpptgkbjq6m:05885] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b3069eb2c]
[pkrvmpptgkbjq6m:05885] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b3064527e]
[pkrvmpptgkbjq6m:05885] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b306288ff]
[pkrvmpptgkbjq6m:05885] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b30aa5ff5]
[pkrvmpptgkbjq6m:05885] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b30abb0da]
[pkrvmpptgkbjq6m:05885] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b30aa5a55]
[pkrvmpptgkbjq6m:05885] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b30aa5a6f]
[pkrvmpptgkbjq6m:05885] [ 8] plumed_master(+0x146dd)[0x55ced09896dd]
[pkrvmpptgkbjq6m:05885] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b3062a1ca]
[pkrvmpptgkbjq6m:05885] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b3062a28b]
[pkrvmpptgkbjq6m:05885] [11] plumed_master(+0x15365)[0x55ced098a365]
[pkrvmpptgkbjq6m:05885] *** End of error message ***
</pre>
{% endraw %}
