**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/di_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1719-82:66527] *** Process received signal ***
[fv-az1719-82:66527] Signal: Aborted (6)
[fv-az1719-82:66527] Signal code:  (-6)
[fv-az1719-82:66527] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7317c45330]
[fv-az1719-82:66527] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7317c9eb2c]
[fv-az1719-82:66527] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7317c4527e]
[fv-az1719-82:66527] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7317c288ff]
[fv-az1719-82:66527] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73180a5ff5]
[fv-az1719-82:66527] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73180bb0da]
[fv-az1719-82:66527] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73180a5a55]
[fv-az1719-82:66527] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73180a5a6f]
[fv-az1719-82:66527] [ 8] plumed_master(+0x146dd)[0x557aea1896dd]
[fv-az1719-82:66527] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7317c2a1ca]
[fv-az1719-82:66527] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7317c2a28b]
[fv-az1719-82:66527] [11] plumed_master(+0x15365)[0x557aea18a365]
[fv-az1719-82:66527] *** End of error message ***
</pre>
{% endraw %}
