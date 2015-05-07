[Home](Home.md)

public static DateTime StripMilliseconds(this DateTime dt)

public static DateTime StripSeconds(this DateTime dt)

public static DateTime StripHours(this DateTime dt)

public static bool IsLegalSqlDate(this DateTime dt)

public static DateTime AddQuarters(this DateTime dt, int quarters)

public static DateTime? StripMilliseconds(this DateTime? dt)

public static DateTime? StripSeconds(this DateTime? dt)

public static DateTime? StripHours(this DateTime? dt)

public static bool IsLegalSqlDate(this DateTime? dt)

public static DateTime? AddMonths(this DateTime? dt, int months)

public static DateTime? AddQuarters(this DateTime? dt, int quarters)

public static DateTime FirstDayOfQuarter(this string yearQuarter)

public static DateTime FirstDayOfQuarter(this int yearQuarter)

public static DateTime FirstDayOfQuarter(this DateTime dt)

public static bool IsFirstDayOfQuarter(this DateTime dt)

public static DateTime ImmediateFirstOfQuarter(this DateTime dt)

public static DateTime FirstDayOfNextQuarter(this DateTime dt)

public static DateTime FirstDayOfPreviousQuarter(this DateTime dt)

public static DateTime FirstDayOfNextNextQuarter(this DateTime dt)

public static DateTime LastDayOfCurrentQuarter(this DateTime dt)

public static DateTime LastDayOfNextQuarter(this DateTime dt)

public static bool IsFirstDayOfMonth(this DateTime dt)

public static bool? IsFirstDayOfMonth(this DateTime? dt)

public static DateTime ImmediateFirstOfMonth(this DateTime dt)

public static DateTime FirstDayOfNextMonth(this DateTime dt)

public static int DaysBetween(this DateTime startDate, DateTime endDate)

public static int MonthsBetween(this DateTime startDate, DateTime endDate)

public static int QuartersBetween(this DateTime startDate, DateTime endDate)

public static DateTime ImmediateFirstOfYear(this DateTime dt)

public static DateTime FirstDayOfNextYear(this DateTime dt)

public static DateTime FirstDayOfMonth(this DateTime dt)

public static DateTime LastDayOfMonth(this DateTime dt)

public static int NumberOfDaysInYear(this DateTime date)

public static int AgeInYears(this DateTime birth, DateTime dt)

public static bool IsConsecutiveSequence<T>(this IEnumerable<T> lst, Func<T, DateTime?> extractDateBegin, Func<T, DateTime?> extractDateEnd) where T : class

