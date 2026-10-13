# Gregorian–Hijri Date Converter – خوارزميات تحويل التاريخ في حاسبتي

**Hasbati Date Conversion Algorithms** is a date-conversion project focused on converting dates between the Gregorian calendar and the Hijri (Islamic) calendar. It documents the fundamental concepts and computational considerations involved in calendar conversion, including differences in month lengths, leap years, and the lunar basis of the Hijri calendar.

Developed as part of **Hasbati (حاسبتي)**, this project supports the broader goal of making date and time calculations easier to understand and integrate into practical digital tools.

## Overview

The Gregorian and Hijri calendars follow different systems for organizing dates. The Gregorian calendar is solar-based, whereas the Hijri calendar is lunar-based, with months corresponding to lunar cycles. Consequently, dates in the two calendars do not maintain a fixed relationship from year to year.

Reliable date conversion requires an appropriate calendar calculation method and a clear understanding of the Hijri calendar convention used by the implementation.

This project focuses on the core concepts behind converting dates in both directions and their applications in date-related software.

## Supported Conversion Directions

### 1. Gregorian to Hijri

Convert a Gregorian date into its corresponding Hijri date.

This conversion is useful for identifying the Hijri equivalent of a date used in Gregorian-based systems, including dates for appointments, records, historical references, and future planning.

**Example input:** A Gregorian date such as `2026-10-13`.

The conversion returns the corresponding Hijri date according to the calendar system and calculation method supported by the implementation.

### 2. Hijri to Gregorian

Convert a Hijri date into its corresponding Gregorian date.

This conversion helps users and developers work with Hijri dates in applications that store, process, or display Gregorian dates.

The result depends on the Hijri calendar convention used by the conversion algorithm.

## Key Features and Technical Considerations

- **Bidirectional Conversion:** Support Gregorian-to-Hijri and Hijri-to-Gregorian conversion, where implemented.
- **Calendar-Aware Calculations:** Account for differences between solar and lunar calendar systems.
- **Variable Month Lengths:** Handle the different month lengths defined by the relevant calendar convention.
- **Leap Year Handling:** Apply the appropriate leap-year rules for each calendar system.
- **Date Validation:** Check that input dates are valid according to the supported calendar rules.
- **Reusable Calculation Logic:** Make conversion functionality suitable for integration into compatible applications.
- **Practical Date Applications:** Support calendar conversion workflows for websites, utilities, and date-related software.

## Understanding Hijri Calendar Variations

The Hijri calendar is based on lunar months, which typically contain 29 or 30 days. However, the exact dates assigned to Hijri months may vary depending on the calendar convention or observation method.

Implementations may use different approaches, including:

- **Tabular Islamic Calendar:** Uses predefined mathematical rules to calculate Hijri dates.
- **Umm al-Qura Calendar:** Uses the official Saudi calendar convention for determining dates within its supported range.
- **Moon-Sighting-Based Calendars:** Determine the beginning of months using crescent-moon observations and the applicable local or religious authority.

These methods are not always interchangeable. Therefore, a conversion result should be interpreted according to the specific calendar system supported by the implementation.

## Accuracy and Validation

Accurate date conversion depends on more than the conversion formula alone. Developers should consider the following:

- Validate input dates before attempting conversion.
- Use a clearly defined calendar convention.
- Test dates near the beginning and end of Hijri months.
- Verify leap-year and month-length behavior.
- Test historical and future dates within the supported range.
- Account for differences between calculated calendar dates and officially announced dates when relevant.

For applications that require official Saudi Hijri dates, the selected conversion method should be checked against the applicable Umm al-Qura calendar data or authoritative references.

## Interactive Date Conversion Tools

You can use the official Hasbati online calculators to convert dates without writing code.

- **[Gregorian to Hijri Converter – تحويل التاريخ من ميلادي إلى هجري](https://hasbati.com/gregorian-hijri-converter/)**  
  Convert Gregorian dates to their Hijri equivalents using the conversion method supported by the online tool.

- **[Hijri to Gregorian Converter – تحويل التاريخ من هجري إلى ميلادي](https://hasbati.com/hijri-gregorian-converter/)**  
  Convert Hijri dates to their corresponding Gregorian dates through an interactive interface.

These tools provide a convenient way to perform everyday date conversions and explore the relationship between the two calendar systems.

## About Hasbati

**Hasbati (حاسبتي)** is an online platform offering practical calculators and digital utilities for mathematical, financial, calendar, and date-related tasks. Its tools are designed to make common calculations more accessible and easier to use.

Explore more calculators and date utilities on the official website:

**[Hasbati.com – Online Calculators](https://hasbati.com/)**

## License

Refer to the repository's `LICENSE` file for the applicable licensing terms.
