# Naming Conventions

Guidelines for choosing descriptive variable and function names in this project.

## Variables

| Avoid | Prefer | Why |
|-------|--------|-----|
| `d` | `elapsedDays` | Clarifies the unit and meaning |
| `tmp` | `unsortedItems` | Describes what the value holds |
| `val` | `accountBalance` | Reveals intent at a glance |
| `list` | `activeUsers` | Specifies what the list contains |
| `flag` | `isVerified` | Indicates a boolean with the `is` prefix |
| `arr` | `monthlyRevenues` | Names the data, not the structure |
| `res` | `apiResponse` | Makes the origin clear |
| `cb` | `onUploadComplete` | Describes when the callback fires |
| `e` | `validationError` | Distinguishes the error type |
| `num` | `retryCount` | States exactly what is counted |

## Functions

| Avoid | Prefer | Why |
|-------|--------|-----|
| `handle()` | `handleFormSubmission()` | States what is being handled |
| `process()` | `processPaymentRefund()` | Specifies the operation |
| `get()` | `getUserProfile()` | Names the resource retrieved |
| `calc()` | `calculateShippingCost()` | Describes the computation |
| `check()` | `validateEmailAddress()` | Clarifies the validation target |
| `do()` | `sendNotificationEmail()` | Expresses the action taken |
| `run()` | `executeScheduledTask()` | Explains what is being executed |
| `init()` | `initializeDatabaseConnection()` | Names the resource initialized |
| `update()` | `updateBillingAddress()` | Identifies what is updated |
| `make()` | `createInvoicePdf()` | Specifies the created artifact |

## Quick Rules

1. **Use full words** — `customerAddress` instead of `custAddr`.
2. **Booleans start with `is`, `has`, or `can`** — `isActive`, `hasPermission`, `canEdit`.
3. **Functions start with a verb** — `fetchOrderHistory()`, `removeExpiredTokens()`.
4. **Collections use plural nouns** — `products`, `selectedItems`.
5. **Constants use UPPER_SNAKE_CASE** — `MAX_RETRY_ATTEMPTS`, `DEFAULT_PAGE_SIZE`.
