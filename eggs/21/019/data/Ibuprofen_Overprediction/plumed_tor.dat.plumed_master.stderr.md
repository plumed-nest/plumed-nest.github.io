**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[fv-az805-507:11642] *** Process received signal ***
[fv-az805-507:11642] Signal: Aborted (6)
[fv-az805-507:11642] Signal code:  (-6)
[fv-az805-507:11642] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f45fbe45330]
[fv-az805-507:11642] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f45fbe9eb2c]
[fv-az805-507:11642] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f45fbe4527e]
[fv-az805-507:11642] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45fbe288ff]
[fv-az805-507:11642] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45fc2a5ff5]
[fv-az805-507:11642] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45fc2bb0da]
[fv-az805-507:11642] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45fc2a5a55]
[fv-az805-507:11642] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45fc2a5a6f]
[fv-az805-507:11642] [ 8] plumed_master(+0x146dd)[0x5621844ca6dd]
[fv-az805-507:11642] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f45fbe2a1ca]
[fv-az805-507:11642] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f45fbe2a28b]
[fv-az805-507:11642] [11] plumed_master(+0x15365)[0x5621844cb365]
[fv-az805-507:11642] *** End of error message ***
</pre>
{% endraw %}
