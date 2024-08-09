**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[fv-az693-738:04390] *** Process received signal ***
[fv-az693-738:04390] Signal: Aborted (6)
[fv-az693-738:04390] Signal code:  (-6)
[fv-az693-738:04390] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb7aec42520]
[fv-az693-738:04390] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb7aec969fc]
[fv-az693-738:04390] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb7aec42476]
[fv-az693-738:04390] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb7aec287f3]
[fv-az693-738:04390] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb7af0a2b9e]
[fv-az693-738:04390] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb7af0ae20c]
[fv-az693-738:04390] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb7af0ae277]
[fv-az693-738:04390] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb7af0ae52b]
[fv-az693-738:04390] [ 8] plumed_master(+0x14274)[0x55b2933c9274]
[fv-az693-738:04390] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb7aec29d90]
[fv-az693-738:04390] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb7aec29e40]
[fv-az693-738:04390] [11] plumed_master(+0x14ed5)[0x55b2933c9ed5]
[fv-az693-738:04390] *** End of error message ***
</pre>
{% endraw %}
