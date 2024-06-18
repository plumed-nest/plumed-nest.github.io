**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action PDB2CONSTANT with label @s1259 : argument O1O_lessthan was not set in pdb input
[fv-az1215-453:10131] *** Process received signal ***
[fv-az1215-453:10131] Signal: Aborted (6)
[fv-az1215-453:10131] Signal code:  (-6)
[fv-az1215-453:10131] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4d86c42520]
[fv-az1215-453:10131] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4d86c969fc]
[fv-az1215-453:10131] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4d86c42476]
[fv-az1215-453:10131] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4d86c287f3]
[fv-az1215-453:10131] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f4d870a2b9e]
[fv-az1215-453:10131] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f4d870ae20c]
[fv-az1215-453:10131] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f4d870ae277]
[fv-az1215-453:10131] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4d870ae52b]
[fv-az1215-453:10131] [ 8] plumed_master(+0x14274)[0x55ceb916b274]
[fv-az1215-453:10131] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4d86c29d90]
[fv-az1215-453:10131] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4d86c29e40]
[fv-az1215-453:10131] [11] plumed_master(+0x14ed5)[0x55ceb916bed5]
[fv-az1215-453:10131] *** End of error message ***
</pre>
{% endraw %}
