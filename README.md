# Verify-Tests-of-i-Tem

Compare Tests of Test Session "Daily" with the Test Session "All".

The goal is verify if is a test in the session "All Tests" that is working, but not is in "Daily Tests" yet.

Step by Step:
Import the Test Session from i-Tem: 
	Test Lab -> Enter in a Test Session
		Click in TestExecution -> Report -> Test cases report (automatic)
			Save the Test Session All with "all_tests"
			Save the Test Session Daily with "daily_tests"

			Both files will be with the extention ".xls"

Open the CMD and type: python verify.py

See the results:
	The ids that was Passed in "All" and aren't in the "Daily"
