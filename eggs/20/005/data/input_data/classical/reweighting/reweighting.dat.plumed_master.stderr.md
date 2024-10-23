**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @16 : keyword ARG is compulsory for this action
[fv-az1442-469:09129] *** Process received signal ***
[fv-az1442-469:09129] Signal: Aborted (6)
[fv-az1442-469:09129] Signal code:  (-6)
[fv-az1442-469:09129] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9e57642520]
[fv-az1442-469:09129] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9e576969fc]
[fv-az1442-469:09129] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9e57642476]
[fv-az1442-469:09129] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9e576287f3]
[fv-az1442-469:09129] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9e57aa2b9e]
[fv-az1442-469:09129] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9e57aae20c]
[fv-az1442-469:09129] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9e57aae277]
[fv-az1442-469:09129] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9e57aae52b]
[fv-az1442-469:09129] [ 8] plumed_master(+0x14254)[0x55bd4483b254]
[fv-az1442-469:09129] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9e57629d90]
[fv-az1442-469:09129] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9e57629e40]
[fv-az1442-469:09129] [11] plumed_master(+0x14eb5)[0x55bd4483beb5]
[fv-az1442-469:09129] *** End of error message ***
</pre>
{% endraw %}
