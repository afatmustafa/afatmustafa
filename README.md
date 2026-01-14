```typescript
export class About {
  public getCurrentWorkplace(): { workplace: Workplace } {
    return {
      workplace: {
        company: "Miova",
        website: "miova.com.tr",
        position: "Co-Owner & CTO",
      },
    };
  }

  public getDailyKnowledge(): DailyKnowledge {
    return {
      backend: ["Laravel", "Hono"],
      frontend: ["TypeScript", "Next.js"],
    };
  }

  public getCurrentlyLearning(): string[] {
    return ["Expo", "TanStack"];
  }

  public getFutureGoal(): string {
    return "To contribute to meaningful open source projects and help grow the ecosystem.";
  }

  public getSocials(): Socials {
    return {
      website: "https://afat.me",
      twitter: "@afatmus",
      linkedin: "afatmustafa",
      instagram: "@afatmustafa",
    };
  }
}
```
