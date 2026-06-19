# Community Code Samples

This directory contains C# backend code samples related to community interactions.

## Included Files

- `RecipeCommentsController.cs`: Comment API entry point, including comment listing, creation, deletion, and comment likes.
- `RecipeCommentService.cs`: Comment business logic, including permission checks, comment creation, deletion, and like toggling.
- `RecipeLikeService.cs`: Recipe like logic, including transaction handling, concurrency conflict handling, and count updates.
- `RecipeSaveService.cs`: Recipe save logic, including save toggling, category queries, and count statistics.
- `RecipeInteractionService.cs`: User interaction event recording for behavior analytics and recommendation signals.

These files demonstrate the community module's API design, business validation, transaction handling, and interaction data modeling.
