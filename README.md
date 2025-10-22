**How to Use This in GTM**

1. Create the Variable
- Variable Type: Custom JavaScript
- Variable Name: JS - Is Bot Traffic
- Paste the enhanced code above

2. Create a Blocking Trigger
- Trigger Type: Custom Event or Page View
- This trigger fires on: Some Page Views/Events
- Condition: {{JS - Is Bot Traffic}} equals true

3. Add Exception to Your Tags
- Go to each tag (GA4, Facebook Pixel, etc.)
- Add the blocking trigger as an Exception
- This prevents tags from firing when bots are detected
