# ALTDOWN
WinWait("Getting Started Tutorial - TestRun","Getting Started with") If Not WinActive("Getting Started Tutorial - TestRun","Getting Started with")  Then WinActivate("Getting Started Tutorial - TestRun","Getting Started with") WinWaitActive("Getting Started Tutorial - TestRun","Getting Started with") Send("{ALTDOWN}c{ALTUP}") WinWait("TestRun Control","")
