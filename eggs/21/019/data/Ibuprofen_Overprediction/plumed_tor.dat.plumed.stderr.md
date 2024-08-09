**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ATOMS141=9314,9319,9310,9313
Maybe a missing space or a typo?
[fv-az530-623:09283] *** Process received signal ***
[fv-az530-623:09283] Signal: Aborted (6)
[fv-az530-623:09283] Signal code:  (-6)
[fv-az530-623:09283] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7faa22842520]
[fv-az530-623:09283] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7faa228969fc]
[fv-az530-623:09283] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7faa22842476]
[fv-az530-623:09283] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7faa228287f3]
[fv-az530-623:09283] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7faa22ca2b9e]
[fv-az530-623:09283] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7faa22cae20c]
[fv-az530-623:09283] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7faa22cae277]
[fv-az530-623:09283] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7faa22cae52b]
[fv-az530-623:09283] [ 8] plumed(+0x12f48)[0x5637b2e50f48]
[fv-az530-623:09283] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7faa22829d90]
[fv-az530-623:09283] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7faa22829e40]
[fv-az530-623:09283] [11] plumed(+0x131e5)[0x5637b2e511e5]
[fv-az530-623:09283] *** End of error message ***
</pre>
{% endraw %}
