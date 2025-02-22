# Extra tile data

Extra tile data always begins with extra tile type, which is always one byte in size.
It is also possible to change a tile's behavior by assigning it different extra tile
type if it already has one, but this might lead into some client-side crashes.

Extra tile data types:
- [000 - No extra data](type000.md)
- [001 - Door](type001.md)
- [002 - Sign](type002.md)
- [003 - Lock](type003.md)
- [004 - Seed](type004.md)
- 005 - ???
- [006 - Mailbox](type006.md)
- [007 - Bulletin board](type007.md)
- [008 - Dice](type008.md)
- [009 - Provider](type009.md)
- [010 - Achievement block](type010.md)
- [011 - Heart monitor](type011.md)
- [012 - Donation box](type012.md)
- 013 - ???
- [014 - Mannequin](type014.md)
- [015 - Bunny egg](type015.md)
- [016 - Game pack](type016.md)
- [017 - Game generator](type017.md)
- [018 - Xenonite crystal](type018.md)
- [019 - Phone booth](type019.md)
- [020 - Crystal](type020.md)
- [021 - Crime in progress](type021.md)
- 022 - ???
- [023 - Display block](type022.md)
- [024 - Vending machine](type023.md)
- 025 - ???
- 026 - ???
- 027 - ???
- [028 - Giving tree](type024.md)
- [033 - Country flag](type025.md)
- 034 - ???
- 035 - ???
- 036 - ???
- 037 - ???
- 038 - ???
- 039 - ???
- [040 - Weather machine background](type040.md)

Item type to extra tile type conversion (Refer to [Item Types](items_dat/item_types.md) for more info about the item type):
- 2 => 1
- 3 => 3
- 10 => 2
- 13 => 1
- 19 => 4
- 26 => 1
- 33 => 6
- 34 => 7
- 36 => 8
- 38 => 9
- 40 => 10
- 43 => 1
- 46 => 11
- 47 => 12
- 48 => 13
- 49 => 14
- 51 => 15
- 52 => 16
- 53 => 17
- 54 => 18
- 55 => 19
- 56 => 20
- 57 => 21
- 59 => 22
- 61 => 23
- 62 => 24
- 63 => 25
- 65 => 26
- 66 => 27
- 67 => 28
- 68 => 29
- 71 => 30
- 72 => 31
- 73 => 32
- 74 => 33
- 75 => 34
- 76 => 35
- 77 => 36
- 78 => 37
- 79 => 38
- 80 => 39
- 81 => 40
- 82 => 41
- 83 => 43
- 84 => 44
- 85 => 45
- 86 => 33
- 87 => 47
- 88 => 48
- 89 => 49
- 92 => 51
- other => 0
