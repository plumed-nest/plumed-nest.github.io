**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[runnervmvrwv9:07695] *** Process received signal ***
[runnervmvrwv9:07695] Signal: Aborted (6)
[runnervmvrwv9:07695] Signal code:  (-6)
[runnervmvrwv9:07695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc192645330]
[runnervmvrwv9:07695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc19269eb2c]
[runnervmvrwv9:07695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc19264527e]
[runnervmvrwv9:07695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1926288ff]
[runnervmvrwv9:07695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc192aa5ff5]
[runnervmvrwv9:07695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc192abb0da]
[runnervmvrwv9:07695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc192aa5a55]
[runnervmvrwv9:07695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc192aa5a6f]
[runnervmvrwv9:07695] [ 8] plumed(+0x146dd)[0x563ff5f616dd]
[runnervmvrwv9:07695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc19262a1ca]
[runnervmvrwv9:07695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc19262a28b]
[runnervmvrwv9:07695] [11] plumed(+0x15365)[0x563ff5f62365]
[runnervmvrwv9:07695] *** End of error message ***
</pre>
{% endraw %}
