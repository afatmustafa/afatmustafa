```typescript
export class About {
  public getCurrentWorkplaces(): Workplace[] {
    return [
      {
        company: "Fidkeep",
        website: "fidkeep.com",
        position: "Co-Founder & CEO",
      },
      {
        company: "Miova",
        website: "miova.com.tr",
        position: "Co-Owner & CTO",
      },
    ];
  }

  public getDailyKnowledge(): DailyKnowledge {
    return {
      languages: ["TypeScript", "PHP"],
      backend: ["Encore", "Laravel"],
      frontend: ["React", "TanStack Start", "Next.js"],
    };
  }

  public getCurrentlyLearning(): string[] {
    return ["Effect", "Expo"];
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
