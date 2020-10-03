package com.hascode.tutorial;

import me.tongfei.progressbar.ProgressBar;

public class Sample {

  public static void main(String[] args) throws InterruptedException {
    System.out.println("\n");
    try (ProgressBar pb = new ProgressBar("Downloading the internet", 2000)) {
      pb.step();
      Thread.sleep(1_000);
      pb.step();
      Thread.sleep(1_000);

      pb.stepBy(248); // step by n
      Thread.sleep(1_000);

      pb.stepTo(600); // step directly to n
      Thread.sleep(1_000);

      pb.maxHint(2500);
      pb.stepTo(1337);
      pb.stepTo(2500);
      pb.setExtraMessage("Downloading..."); // Set extra message to display at the end of the bar
    }
    System.out.println("we have downloaded the internet ...");
  }
}
