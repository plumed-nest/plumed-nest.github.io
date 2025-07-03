**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmbietmlfzoi:07603] *** Process received signal ***
[pkrvmbietmlfzoi:07603] Signal: Aborted (6)
[pkrvmbietmlfzoi:07603] Signal code:  (-6)
[pkrvmbietmlfzoi:07603] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc241645330]
[pkrvmbietmlfzoi:07603] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc24169eb2c]
[pkrvmbietmlfzoi:07603] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc24164527e]
[pkrvmbietmlfzoi:07603] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2416288ff]
[pkrvmbietmlfzoi:07603] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc241aa5ff5]
[pkrvmbietmlfzoi:07603] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc241abb0da]
[pkrvmbietmlfzoi:07603] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc241aa5a55]
[pkrvmbietmlfzoi:07603] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc241aa5a6f]
[pkrvmbietmlfzoi:07603] [ 8] plumed_master(+0x146dd)[0x561bf0dcf6dd]
[pkrvmbietmlfzoi:07603] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc24162a1ca]
[pkrvmbietmlfzoi:07603] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc24162a28b]
[pkrvmbietmlfzoi:07603] [11] plumed_master(+0x15365)[0x561bf0dd0365]
[pkrvmbietmlfzoi:07603] *** End of error message ***
</pre>
{% endraw %}
