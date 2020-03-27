Module FirstModule
  Sub Main
    Console.Write("Today is ...")
    Console.ForegroundColor.Yellow
    Console.Writeline(DateTimeNow.DayOfWeek.ToString)
    Console.ResetColor
    Console.Read
  End Sub
End Module