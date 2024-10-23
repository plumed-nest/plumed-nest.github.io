**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1442-469:05732] *** Process received signal ***
[fv-az1442-469:05732] Signal: Aborted (6)
[fv-az1442-469:05732] Signal code:  (-6)
[fv-az1442-469:05732] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1b78242520]
[fv-az1442-469:05732] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1b782969fc]
[fv-az1442-469:05732] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1b78242476]
[fv-az1442-469:05732] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1b782287f3]
[fv-az1442-469:05732] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1b786a2b9e]
[fv-az1442-469:05732] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1b786ae20c]
[fv-az1442-469:05732] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1b786ae277]
[fv-az1442-469:05732] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1b786ae52b]
[fv-az1442-469:05732] [ 8] plumed_master(+0x14254)[0x557da98c9254]
[fv-az1442-469:05732] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1b78229d90]
[fv-az1442-469:05732] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1b78229e40]
[fv-az1442-469:05732] [11] plumed_master(+0x14eb5)[0x557da98c9eb5]
[fv-az1442-469:05732] *** End of error message ***
</pre>
{% endraw %}
