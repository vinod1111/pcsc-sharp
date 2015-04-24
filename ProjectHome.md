The PC/SC API provides a standardized interface to Smartcard readers.

The **pcsc-sharp** library represents a wrapper to use either Microsoft's PC/SC implementation (WinSCard) or [pcsc-lite](http://pcsclite.alioth.debian.org/) with implementations of the [Common Language Infrastructure (CLI)](http://www.ecma-international.org/publications/standards/Ecma-335.htm) such as [.NET Framework](http://msdn2.microsoft.com/en-us/netframework/default.aspx) or [Mono](http://www.mono-project.com/). The library itself is written in C#.

The **MCard-sharp** library is a wrapper for the MCard API of [SCM Microsystems](http://www.scmmicro.com/), to be used on top of pcsc-sharp. It provides access to memory smart cards, in addition to the processor smart cards supported by PC/SC.

The **Smartcard Commands** library provides managed helpers to create, transmit and evaluate ISO-7816-4 commands for processor smart cards via pcsc-sharp. _Note that this library is under 2-clause BSD license._