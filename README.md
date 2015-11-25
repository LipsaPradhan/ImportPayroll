# ImportPayroll
Payroll Inbound Reports For RosterOn.

## Helpful Code Snippets

To check if a date exists and if it doesn't default the date to 01/01/2049 otherwise format it to "dd/MM/yyyy"
'''
=Format(Cdate(IIF(LEN(Fields!Column05.Value)>0,Fields!Column05.Value,"01/01/2049")),"dd/MM/yyyy")
'''
