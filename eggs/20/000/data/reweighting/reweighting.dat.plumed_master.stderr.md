**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[fv-az1442-469:09438] *** Process received signal ***
[fv-az1442-469:09438] Signal: Aborted (6)
[fv-az1442-469:09438] Signal code:  (-6)
[fv-az1442-469:09438] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2657842520]
[fv-az1442-469:09438] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f26578969fc]
[fv-az1442-469:09438] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2657842476]
[fv-az1442-469:09438] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f26578287f3]
[fv-az1442-469:09438] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2657ca2b9e]
[fv-az1442-469:09438] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2657cae20c]
[fv-az1442-469:09438] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2657cae277]
[fv-az1442-469:09438] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2657cae52b]
[fv-az1442-469:09438] [ 8] plumed_master(+0x14254)[0x55888ca77254]
[fv-az1442-469:09438] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2657829d90]
[fv-az1442-469:09438] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2657829e40]
[fv-az1442-469:09438] [11] plumed_master(+0x14eb5)[0x55888ca77eb5]
[fv-az1442-469:09438] *** End of error message ***
</pre>
{% endraw %}
