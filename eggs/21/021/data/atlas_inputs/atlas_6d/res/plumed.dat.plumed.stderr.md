**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1720-841:09157] *** Process received signal ***
[fv-az1720-841:09157] Signal: Aborted (6)
[fv-az1720-841:09157] Signal code:  (-6)
[fv-az1720-841:09157] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f049d645330]
[fv-az1720-841:09157] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f049d69eb2c]
[fv-az1720-841:09157] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f049d64527e]
[fv-az1720-841:09157] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f049d6288ff]
[fv-az1720-841:09157] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f049daa5ff5]
[fv-az1720-841:09157] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f049dabb0da]
[fv-az1720-841:09157] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f049daa5a55]
[fv-az1720-841:09157] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f049daa5a6f]
[fv-az1720-841:09157] [ 8] plumed(+0x146dd)[0x5603b09d56dd]
[fv-az1720-841:09157] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f049d62a1ca]
[fv-az1720-841:09157] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f049d62a28b]
[fv-az1720-841:09157] [11] plumed(+0x15365)[0x5603b09d6365]
[fv-az1720-841:09157] *** End of error message ***
</pre>
{% endraw %}
