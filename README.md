# AAESOptimisationExamples
Audio examples for the paper "Closed-Loop Differentiable Optimisation for Active Acoustics".
Please view this on [GitHub pages](https://iosr-surrey.github.io/AAESOptimisationExamples/).
# Task 1: Colouration Reduction (open- vs closed-loop)
Power spectrograms from one test position in the Room 1 16 × 16 AAES comparing the unequalised condition (a) to the open- (b) and closed-loop (c) results.
<div style="display:flex;flex-direction:row;gap:16px;align-items:stretch;">
  <img style="width:400px;height:457px;" alt="Large System Spectrograms" src="https://github.com/user-attachments/assets/1e63b576-08df-4387-be7a-0d03501992e3"/>
  <div style="display:flex;flex-direction:column;gap:8px;">
    <h2>Impulse Responses</h2>
    <div style="display:flex;flex-direction:column;justify-content:flex-start;">
      <div>
        <h4 style="margin:0 8px 4px 0;">Passive Room</h4>
        <audio controls>
          <source src="Audio/Fig 4 IRs/16x16_passive-room_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">a. No Equalisation</h4>
        <audio controls>
          <source src="Audio/Fig 4 IRs/16x16_no-eq_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">b. Optimised (Open-Loop)</h4>
        <audio controls>
          <source src="Audio/Fig 4 IRs/16x16_open-loop_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">c. Optimised (Closed-Loop)</h4>
        <audio controls>
          <source src="Audio/Fig 4 IRs/16x16_closed-loop_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
    </div>
  </div>
  <div style="display:flex;flex-direction:column;gap:8px;">
    <h2>Saxophone Convolution</h2>
    <div style="display:flex;flex-direction:column;justify-content:flex-start;">
      <div>
        <h4 style="margin:0 8px 4px 0;">Passive Room</h4>
        <audio controls>
          <source src="Audio/Fig 4 Conv/16x16_passive-room_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">a. No Equalisation</h4>
        <audio controls>
          <source src="Audio/Fig 4 Conv/16x16_no-eq_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">b. Optimised (Open-Loop)</h4>
        <audio controls>
          <source src="Audio/Fig 4 Conv/16x16_open-loop_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">c. Optimised (Closed-Loop)</h4>
        <audio controls>
          <source src="Audio/Fig 4 Conv/16x16_closed-loop_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
    </div>
  </div>
</div>

# Task 2 - Late Reverberation Matching (closed-loop)
Power spectrograms of (a) the passive RIR of Room 1, (b) the target RIR, and (c) the optimised Room 1 16 × 16 AAES. Dashed white lines indicate the −30 dB profile with half-octave-band resolution.
<div style="display:flex;flex-direction:row;gap:16px;align-items:stretch;">
  <img style="width:400px;height:457px;" alt="EDC Matching Spectrograms" src="https://github.com/user-attachments/assets/c969c87d-e449-41f8-b06a-8c29eaff4ff9"/>
  <div style="display:flex;flex-direction:column;gap:8px;">
    <h2>Impulse Responses</h2>
    <div style="display:flex;flex-direction:column;justify-content:flex-start;">
      <div>
        <h4 style="margin:0 8px 4px 0;">a. Passive Room</h4>
        <audio controls>
          <source src="Audio/Fig 5 IRs/passive_room_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">b. Target</h4>
        <audio controls>
          <source src="Audio/Fig 5 IRs/target_room.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">c. Optimised</h4>
        <audio controls>
          <source src="Audio/Fig 5 IRs/16x16_edc_matching_optimised_R1_S3.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">Optimised (modified*)</h4>
        <audio controls>
          <source src="Audio/Fig 5 IRs/16x16_edc_matching_optimised_early_mod.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
    </div>
  </div>
  <div style="display:flex;flex-direction:column;gap:8px;">
    <h2>Saxophone Convolution</h2>
    <div style="display:flex;flex-direction:column;justify-content:flex-start;">
      <div>
        <h4 style="margin:0 8px 4px 0;">a. Passive Room</h4>
        <audio controls>
          <source src="Audio/Fig 5 Conv/passive_room_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">b. Target</h4>
        <audio controls>
          <source src="Audio/Fig 5 Conv/target_room_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">c. Optimised</h4>
        <audio controls>
          <source src="Audio/Fig 5 Conv/16x16_edc_matching_optimised_R1_S3_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
      <div>
        <h4 style="margin:0 8px 4px 0;">Optimised (modified*)</h4>
        <audio controls>
          <source src="Audio/Fig 5 Conv/16x16_edc_matching_optimised_early_mod_convolved.wav" type="audio/wav">
          Open on GitHub pages to view audio player (link above)
        </audio>
      </div>
    </div>
  </div>
</div>

\*To provide more comparable early energy, the impulse responses of these examples were constructed by crossfading from the target to the optimised result (between 50 and 100 ms relative to the direct impulse).
